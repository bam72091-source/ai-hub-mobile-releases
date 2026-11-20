# AI Hub Mobile – releases

Update feed for the AI Hub Mobile Android app. This repo holds only:

- `latest.json` – the newest version number, its download link and its SHA-256 checksum.
- APK files attached to each GitHub Release.

No source code and no keys live here. The app checks `latest.json`, downloads the APK over https,
verifies the checksum and package name, then opens Android's installer. Android also refuses any
update that isn't signed with the same key as the installed app.

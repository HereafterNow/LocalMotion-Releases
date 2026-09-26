# LocalMotion-Releases

Public release-asset host for the **LocalMotion** desktop app (Windows GIF
editor). The app's built-in updater (Help > Check for Updates, v1.1.0+)
fetches `latest.json` from the newest release here.

## Layout per release

- `LocalMotion-v<version>-windows-x64.zip` - the hand-out zip
  (LocalMotion.exe + updater.exe + README.txt)
- `LocalMotion-<version>.exe` - the bare app exe the updater downloads
- `latest.json` - the update manifest: `version`, `url`, `sha256`, `notes`

The editor core is open source (GPL-2.0):
https://github.com/HereafterNow/LocalMotion
# 日晷 DayDial — releases

Installers and update feeds for 日晷 (DayDial). The source code is private; this repo only
holds what the apps need to update themselves.

| Device | Download (latest) |
|---|---|
| iPhone / iPad (sign it yourself) | `DayDial-<version>-iPhone-iPad.ipa` in [Releases](../../releases/latest) |
| Mac (Apple Silicon + Intel) | `DayDial-<version>-Mac-universal.dmg` |
| Windows | `DayDial-<version>-Windows-Setup.exe` |

## Update feeds

- Mac and Windows check `releases/latest/download/latest.json` and offer **更新并重启**.
  Updates are signed; the apps refuse anything without the matching signature.
- iPhone/iPad checks `releases/latest/download/version.json` and shows **有新版本**.
- Signing tools that support sources (AltStore, SideStore, ESign, Feather, Scarlet, …) can add:

  ```
  https://github.com/M2-King/daydial-releases/releases/latest/download/source.json
  ```

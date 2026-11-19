# ManuNotes Releases (Windows/Linux)

Built installers for [ManuNotes](https://manunotes.app.br) on Windows and
Linux — an edge-docked notes widget, ported from the native macOS app.
Source code lives in the private
[ManuNotes-Electron](https://github.com/edgoapp/ManuNotes-Electron)
repo; this repo only holds release artifacts.

## Download

Most PCs are x64 — grab one of these (always the latest release):

- **Windows**: [ManuNotes-Setup-x64.exe](https://github.com/edgoapp/ManuNotes-Electron-releases/releases/latest/download/ManuNotes-Setup-x64.exe)
- **Linux**: [ManuNotes-x86_64.AppImage](https://github.com/edgoapp/ManuNotes-Electron-releases/releases/latest/download/ManuNotes-x86_64.AppImage)
  (make it executable — `chmod +x ManuNotes-x86_64.AppImage` — then run
  it directly)

Windows on Arm, the portable `.exe` (no install needed), the arm64
AppImage, and the `.deb` package are all on the
[Releases](../../releases) page.

### "Windows protected your PC" / unsigned warning

ManuNotes isn't code-signed yet (that requires a paid code-signing
certificate), so Windows SmartScreen and some Linux package managers may
flag it as unrecognized. On Windows, click **More info → Run anyway** in
the SmartScreen dialog.

## Versions

Releases here follow their own version numbers, independent of the
macOS app's — see the source repo's `CHANGELOG.md` for what changed in
each one.

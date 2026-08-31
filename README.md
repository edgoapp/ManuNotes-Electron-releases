# ManuNotes Releases (Windows/Linux)

Built installers for [ManuNotes](https://manunotes.app.br) on Windows and
Linux — an edge-docked notes widget, ported from the native macOS app.
Source code lives in the private
[ManuNotes-Electron](https://github.com/ManuNotes/ManuNotes-Electron)
repo; this repo only holds release artifacts.

## Download

Grab the latest installer from [Releases](../../releases):

- **Windows**: `ManuNotes-Setup.exe` (installer) or `ManuNotes.exe`
  (portable, no install needed).
- **Linux**: `ManuNotes.AppImage` (make it executable — `chmod +x
  ManuNotes.AppImage` — then run it directly) or `ManuNotes.deb`
  (`sudo apt install ./ManuNotes.deb` on Debian/Ubuntu-based distros).

Stable direct-download links (always the latest release, no version in
the URL):

- `https://github.com/ManuNotes/ManuNotes-Electron-releases/releases/latest/download/ManuNotes-Setup.exe`
- `https://github.com/ManuNotes/ManuNotes-Electron-releases/releases/latest/download/ManuNotes.exe`
- `https://github.com/ManuNotes/ManuNotes-Electron-releases/releases/latest/download/ManuNotes.AppImage`
- `https://github.com/ManuNotes/ManuNotes-Electron-releases/releases/latest/download/ManuNotes.deb`

### Current builds are arm64 only

These builds target arm64 (Windows on ARM, Linux arm64/aarch64). x64
("regular" Windows/Linux PCs) isn't covered yet — see the source repo's
README for why (a native-module cross-compilation limitation) and what
full coverage would take.

### "Windows protected your PC" / unsigned warning

ManuNotes isn't code-signed yet (that requires a paid code-signing
certificate), so Windows SmartScreen and some Linux package managers may
flag it as unrecognized. On Windows, click **More info → Run anyway** in
the SmartScreen dialog.

## Versions

Releases here follow their own version numbers, independent of the
macOS app's — see the source repo's `CHANGELOG.md` for what changed in
each one.

# Chimku — releases

Installers for the Chimku desktop app (Windows, macOS, Linux). Each release carries
the installers plus the `latest*.yml` files the app's auto-updater reads.

- Windows: `Chimku-Setup-<version>.exe` (NSIS, x64)
- macOS: `Chimku-<version>-<arch>.dmg` / `.zip`
- Linux: `Chimku-<version>-x86_64.AppImage`, `.deb`

Builds are currently unsigned: Windows SmartScreen and macOS Gatekeeper will warn on
first launch. Source and issues live in the private product repository.

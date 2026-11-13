# RTS Releases

Public Windows x64 releases and auto-update manifests for RTS (`stable` and `prerelease` channels).

## Installation & Updates (All Windows x64 PCs — Desktop & Laptop)

Starting with `0.8.0-rc.7`, **one unified Windows x64 ZIP** (`Rts-<version>-Windows-x64.zip`, containing `Rts.exe`, `Rts.pck`, `Play RTS.cmd`, and `RtsUpdater.exe`) serves both desktop and laptop PCs:

1. Download `Rts-<version>-Windows-x64.zip` from [Releases](https://github.com/gwhitdev/rts-releases/releases) and extract it to a folder.
2. Run `Play RTS.cmd` (or `RtsUpdater.exe`) to launch and check for updates on your chosen channel (`stable` or `prerelease`).

## Migrating from Legacy Embedded Laptop Builds (`0.8.0-rc.6` and earlier)

- Earlier `Rts-*-Laptop-Windows-x64.zip` (`Rts-Laptop.exe`) releases are preserved untouched for immutability, but will not auto-upgrade to the unified package.
- To migrate: download and extract the unified `Rts-<version>-Windows-x64.zip` into a fresh folder and launch via `Play RTS.cmd`. Your `user://` saves, settings, and imported `.rtsmap` maps in `%APPDATA%` are preserved automatically.
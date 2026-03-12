# Release Notes

## v0.1.1

Creator Asset Studio `v0.1.1` sharpens the desktop workflow with a more usable Export Studio layout, cleaner table real estate, refreshed branding, and a fix for the scan-start regression that could leave the queue at `0%`.

### Highlights

- More accessible Export Studio layout with adjustable workspace focus modes
- Real app icon and compact in-app credits linked to the public repository
- Cleaner media browser table with the non-functional preview column removed
- Scan worker fix so source scans start and complete normally again
- Updated Windows installer for the `v0.1.1` release

### Distribution

- Installer file: `CreatorAssetStudio-Setup.exe`
- Delivery channel: GitHub Releases
- Source availability: private repository, available by request
- SHA-256: `D02D9F7E896A715DF136983D7E1D01E97322FEAA0DB49E04F4F71070BA66CF03`

### Installation Notes

This release is currently distributed as an unsigned Windows installer.

- Some systems may show the Microsoft Defender SmartScreen warning:
  - `Windows protected your PC`
  - `Microsoft Defender SmartScreen prevented an unrecognized app from starting. Running this app might put your PC at risk.`
- If you downloaded the installer from the official GitHub Releases page, the usual path is:
  - `More info`
  - `Run anyway`
- Some antivirus products may block setup while it extracts files to the Windows temporary directory. If that happens, installation can fail with:
  - `Unable to execute file in the temporary directory. Setup aborted.`
  - `Error 5: Access is denied.`
- If needed, temporarily allowlist the installer or briefly pause real-time protection during install, then turn protection back on immediately after setup completes.

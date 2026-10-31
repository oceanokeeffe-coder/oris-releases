# ORIS for Windows

**[Get the latest approved ORIS Beta for Windows](https://github.com/oceanokeeffe-coder/oris-releases/releases/latest)**

Open the release page and download **ORIS-Setup.exe** from **Assets**. Its version
appears in the release title and release notes. Open the installer, then launch
**ORIS Beta** from Start and create or open a local profile.

[Direct Windows installer](https://github.com/oceanokeeffe-coder/oris-releases/releases/latest/download/ORIS-Setup.exe)

Windows 10/11 x64. No Codex, development tools, ChatGPT account or subscription is
needed. A free Microsoft WebView2 runtime may be downloaded during installation
if Windows needs it. ORIS then works offline, with study data stored on your computer.

## Updating

Export a complete profile backup from **Settings → Data & Backups** before major
upgrades. Finish your timer, quit ORIS through its tray and install the newer
approved version under the same Windows account. Keep application data; profiles
and study history should be preserved.

ORIS 0.1.0 cannot update itself and needs a manual installer upgrade. Newer builds
prepare in-app update controls, but the public updater still needs end-to-end
verification. Use manual installers until that testing is confirmed. Automatic
update checks default off, and installation always requires your approval.

## Windows security warnings

The installer does not have a Windows Authenticode publisher certificate. Windows
may show an Unknown publisher or SmartScreen warning. Verify this release and its
SHA256SUMS.txt before deciding whether to install. Do not disable Windows security.
Tauri's separate updater signatures do not remove publisher/reputation warnings.

This repository contains download documentation and release assets only. The
application source and all personal data remain separate. Automatic source archives
contain this download repository's documentation, not the ORIS application source.

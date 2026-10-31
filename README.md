# ORIS for Windows

ORIS is an offline study timer, planner and study diary for Windows 10/11 x64.

**No public installer has been published yet. Downloads are awaiting owner approval.**

The permanent release-page address will be:
https://github.com/oceanokeeffe-coder/oris-releases/releases/latest

This address does not provide a download until the first approved release is published.
Do not send it as a live download invitation yet.

## Installing an approved release

1. Open the release-page address above after publication.
2. Download **ORIS-Setup.exe** from Assets. Its version appears in the release title and notes.
3. Open the installer, then launch **ORIS Beta** from Start.
4. Create a local profile or open your existing one and start studying.

The fixed installer asset address, once published, will be:
https://github.com/oceanokeeffe-coder/oris-releases/releases/latest/download/ORIS-Setup.exe

No Codex, Node.js, Rust, ChatGPT account or subscription is required. A free
Microsoft WebView2 runtime may be downloaded by the installer if Windows needs it.
ORIS then works offline.

## Existing users

Export a complete profile backup from **Settings → Data & Backups** before a major
upgrade. Finish your study session and quit ORIS through its tray before installing
the newer approved version. Use the same Windows account and keep application data.
Your local profiles, projects, notes and study history should remain available.

ORIS 0.1.0 cannot update itself: it needs a manual installer upgrade. Newer builds
prepare **Settings → About ORIS → Check for Updates**. The public update service
has not yet been activated or tested. Automatic checks default off; installation
always needs your approval and must not interrupt running or paused study sessions.
Until public update testing is complete, use the approved manual installer.

## Windows security warnings

The installer is not signed with Windows Authenticode. Windows may show an Unknown
publisher or SmartScreen warning. Verify the release source and SHA-256 checksum
before deciding whether to install. Do not disable Windows protections. Tauri's
separate cryptographic updater signatures do not provide a Windows publisher certificate.

This is a releases-only repository. Application source, development files and user
data are maintained separately. GitHub's automatic source archives contain only
this repository's download documentation.

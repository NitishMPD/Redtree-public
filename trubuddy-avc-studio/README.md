# TruBuddy AVC Studio for Windows

TruBuddy AVC Studio is a comic production editor for English and Hindi audiovisual editions. Import artwork, review AI extraction proposals, edit dialogue and characters, choose voice takes, direct playback, and add background music or sound effects.

Download the Windows x64 installer from [TruBuddy AVC Studio releases](https://github.com/NitishMPD/Redtree-public/releases?q=trubuddy-avc-studio-v).

## Current release

- [Download 0.1.2 for Windows x64](https://github.com/NitishMPD/Redtree-public/releases/download/trubuddy-avc-studio-v0.1.2/TruBuddy-AVC-Studio-0.1.2-x64-Setup.exe)
- [Installer checksum](https://github.com/NitishMPD/Redtree-public/releases/download/trubuddy-avc-studio-v0.1.2/SHA256SUMS.txt)

The installer includes Node, SQLite, image/PDF tools and the comic Player. Studio starts its local server and background worker automatically. First-run setup offers optional Codex and ElevenLabs connections and a guided editing tutorial. Manual editing and imported sound work without either provider; analysis and generated speech need internet access and the respective credentials.

## Release notes

- [0.1.2: Desktop workspace, tutorial and timeline timing](0.1.2.md)
- [0.1.1: In-app Windows updates](0.1.1.md)
- [0.1.0: First Windows desktop release](0.1.0.md)

Each release has its own versioned Markdown file in this folder. Installers and checksums are attached to the corresponding GitHub Release.

## Install and update

Run the installer to choose an installation folder. If you have 0.1.0, install 0.1.2 manually once. Starting with 0.1.1, Studio checks for updates at startup and every six hours. You can also check in Settings or the Studio menu, download an update, then choose **Restart & install**. Studio checks for active work before restarting. Closing Studio does not install a pending update.

Projects live in the application's user-data folder, separately from the installation, and uninstall retains them. Use Settings to open the project folder. Back up the complete folder with Studio closed before updating.

The 0.1.2 installer is unsigned. Windows may show an unknown-publisher or SmartScreen prompt. Clean-machine installation and live paid-provider workflows have not been validated for this release.

Desktop reader links work on the local computer. Share an exported AVC ZIP or use a hosted workspace for public reader links.

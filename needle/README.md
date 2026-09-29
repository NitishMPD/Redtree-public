# Needle for Windows

Download the latest Windows installer from [Needle releases](https://github.com/NitishMPD/Redtree-public/releases?q=needle-v).

## Release notes

- [0.1.11 — Live previews and Figma import refinements](0.1.11.md)
- [0.1.10 — Figma references in Live projects](0.1.10.md)
- [0.1.9 — Live agent conversation fixes](0.1.9.md)
- [0.1.8 — Live project controls and editing refinements](0.1.8.md)
- [0.1.7 — Live project creation, design systems, in-place editing and shipping](0.1.7.md)
- [0.1.6 — Live mode](0.1.6.md)
- [0.1.5 — Desktop fixes](0.1.5.md)
- [0.1.4 — Startup fix](0.1.4.md)
- [0.1.3](0.1.3.md) · [0.1.2](0.1.2.md) · [0.1.1](0.1.1.md) · [0.1.0](0.1.0.md)

Needle Desktop runs its bundled interface on your computer and can use an installed Codex CLI after `codex login`. Projects and API keys stay in the desktop app's local profile. The desktop app checks this repository for `needle-v<version>` releases and offers a link when an update is available.

Local OpenCode also uses the installed `opencode` CLI and its own login. In Settings, choose **Muse Spark 1.3 Free** to use `opencode/muse-spark-1.3-contributor-free`. OpenCode controls model access through your account.

The source and website are maintained in [NitishMPD/Needle](https://github.com/NitishMPD/Needle). Each desktop release attaches `Needle-Setup-<version>-x64.exe` as a GitHub Release asset. Installers are not stored in Git because of their size. The site and desktop releases can be published separately from the same source version.

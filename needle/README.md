# Needle for Windows

Download the latest Windows installer from [Needle releases](https://github.com/NitishMPD/Redtree-public/releases?q=needle-v).

Needle Desktop runs its bundled interface on your computer and can use an installed Codex CLI after `codex login`. Projects and API keys stay in the desktop app's local profile. The desktop app checks this repository for `needle-v<version>` releases and offers a link when an update is available.

Local OpenCode also uses the installed `opencode` CLI and its own login. OpenCode model access is controlled by the OpenCode account; a free model can still return a provider-side `403 FreeTierError` from the CLI.

The source and website are maintained in [NitishMPD/Needle](https://github.com/NitishMPD/Needle). Each desktop release attaches `Needle-Setup-<version>-x64.exe` as a GitHub Release asset. Installers are not stored in Git because of their size. The site and desktop releases can be published separately from the same source version.

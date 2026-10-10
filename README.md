# R6MC releases

Rainbow Six Siege (Heated Metal) x Minecraft. **Download [R6MC-Setup.exe](R6MC-Setup.exe)** and run it: it installs
everything (see the player guide in the source repo) and becomes the R6MC launcher.

This repo only holds releases. `latest.json` is what the R6MC launcher reads to find and check an update
(version, the setup's address, size and SHA-256). It is written by `tools\publish-release.ps1` in the source repo
(`absolute-dogshit`, branch `main`), never by hand.

Current: **0.3.0**: Improved block placing (lines up with the map), no more Minecraft through walls, per-map grid

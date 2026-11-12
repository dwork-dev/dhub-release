# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.25** (released 2026-11-12)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.25-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.25/dwork-dhub-0.2.25-windows.zip) | `eb6eb4fd1b84a745cb45867c1e17e3606b5115f3e7ac44914ee3ffea1e0b06d2` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.25-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.25/dwork-dhub-0.2.25-macos.pkg) | `e6ee7055a9ee37fdb4adf8e1c915646912b2d1ec19de8deaec23915146e6b8ec` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.25-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.25/dwork-dhub-0.2.25-linux.deb) | `38fff936dec0aa2a7af5fb0d2d89feb5cd9c766a4190afacc54897fd28418451` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.25-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.25/dwork-dhub-0.2.25-linux-arm64.deb) | `350b2670e766adb569f53213d618177085b9c79f07a3cfe8186de1ca60049a77` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

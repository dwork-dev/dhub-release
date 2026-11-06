# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.23** (released 2026-11-05)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.23-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.23/dwork-dhub-0.2.23-windows.zip) | `ffca4f758b56b6993a51694d2c8db10601072a0ff3230a6710ea5a7a3d782292` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.23-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.23/dwork-dhub-0.2.23-macos.pkg) | `bbb3f071ef189e738b02271a53cdfa2e8ee488ff3c98e74ad05f997a1e26acd6` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.23-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.23/dwork-dhub-0.2.23-linux.deb) | `93dcdbb17ebabb462df4552e067e3d7f816f1c299f54cc72e09676c5ccaf49ca` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.23-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.23/dwork-dhub-0.2.23-linux-arm64.deb) | `da0ad5ddf800f8c789514bd77adcd5f4e71bde0cd6651e8d68ade17ff3edd1dd` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

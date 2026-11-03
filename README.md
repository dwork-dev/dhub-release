# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.20** (released 2026-11-03)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.20-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.20/dwork-dhub-0.2.20-windows.zip) | `67cc0d4c00e6ad97225790929bb16366950301a651280d4b6398ed7773385d7b` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.20-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.20/dwork-dhub-0.2.20-macos.pkg) | `efe94e2cbdddc1256b449b98145e0b318389bcfd3349d43f6e6e09fdef78867d` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.20-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.20/dwork-dhub-0.2.20-linux.deb) | `870f391edc3b1995408357dc330644a81e848b54b8b3cc778482fd3689072427` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.20-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.20/dwork-dhub-0.2.20-linux-arm64.deb) | `f17a5a912e8c2b49963c7f4283c816adeaf063b40a685048c8002d57faaa9285` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

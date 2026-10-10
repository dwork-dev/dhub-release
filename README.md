# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.9** (released 2026-10-10)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.9-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.9/dwork-dhub-0.2.9-windows.zip) | `053b544fe7433c5abff777b3c2dd6a077ff60e05e03362d4996950567a6f3388` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.9-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.9/dwork-dhub-0.2.9-macos.pkg) | `6df3698d1579ee320b8d67c8d74354346df7c23a23679950c067f0acbb149bed` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.9-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.9/dwork-dhub-0.2.9-linux.deb) | `26ad4250cf329a5190f370b1caa25d76d5931cfb53b638051f9b8d74f071ca99` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.9-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.9/dwork-dhub-0.2.9-linux-arm64.deb) | `0fb028e9866a736448d72dfce4967b215d4c6a7edc3df0225e6143e5b779acd9` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

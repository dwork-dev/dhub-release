# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.24** (released 2026-11-10)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.24-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.24/dwork-dhub-0.2.24-windows.zip) | `800ff45425bd52ee267f54177a2fab36e531146a47e5e1b8b92c45387dbe8504` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.24-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.24/dwork-dhub-0.2.24-macos.pkg) | `3325b0c6d7da366d469305476f4c992697db2ee6bdd591ea49c2eeadd67bb8ab` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.24-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.24/dwork-dhub-0.2.24-linux.deb) | `be5a012d616a2cf58c0153fffd2b9bba4401c1a4201cda40157e3b2f33db4b62` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.24-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.24/dwork-dhub-0.2.24-linux-arm64.deb) | `53f32ab509f0ad8ae6ea06dbcb98996582c8e08d65694e9e9623a88e7a01cc16` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

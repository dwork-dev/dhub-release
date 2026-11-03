# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.18** (released 2026-11-03)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.18-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.18/dwork-dhub-0.2.18-windows.zip) | `05eafb01deb03419c9bcb879bbbaaea030203247181d88d32f9487f378784bd3` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.18-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.18/dwork-dhub-0.2.18-macos.pkg) | `37295d8c73a38feb40b6630e89c66b67b083da321de55e444cce8c5404c731e1` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.18-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.18/dwork-dhub-0.2.18-linux.deb) | `19bd6f10250c1ca83e38005ea46393e83f850e6b6f384ad958c847a024e764d1` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.18-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.18/dwork-dhub-0.2.18-linux-arm64.deb) | `66b51a5036d757fa2acc38a1db56bb9eb0d4b0e645303ff1928c73fcd2b6defc` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

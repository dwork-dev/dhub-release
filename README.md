# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.5** (released 2026-10-05)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.5-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.5/dwork-dhub-0.2.5-windows.zip) | `bc7b146f02fad190a7e0a4c496f921badb8fbc6d4d6e3fd7f9228ffc368f4c8e` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.5-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.5/dwork-dhub-0.2.5-macos.pkg) | `174381b6e4aa4365dc6cca300a89da53ab243842e9b88d73105371755b3fd6e4` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.5-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.5/dwork-dhub-0.2.5-linux.deb) | `a592b6a55b7334bda1f986dcb9498a0ed598d7e52505ad923b830a8de4a13dc2` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.5-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.5/dwork-dhub-0.2.5-linux-arm64.deb) | `f40f1b72b4a81e5d76449b464a580c50c10b169c12f68ba703eb0c4321198551` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.8** (released 2026-10-06)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.8-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.8/dwork-dhub-0.2.8-windows.zip) | `9e918489ac60675d22c84dd6701272bd4f871a6ad6676c831161530f2d24efc3` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.8-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.8/dwork-dhub-0.2.8-macos.pkg) | `c180903ff36e4b7d6401339d8fd84cd3b42a8b92831061f6754c42c620de3285` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.8-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.8/dwork-dhub-0.2.8-linux.deb) | `3435d110477746078959a58c43f0cb63525cd7c63dcb61676ce6ce31ebf0f774` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.8-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.8/dwork-dhub-0.2.8-linux-arm64.deb) | `c51a5544d7059faa92946e4d0e05d3173ea3e6d2401172187af5fa9984af8e55` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

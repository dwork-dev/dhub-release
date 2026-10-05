# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.4** (released 2026-10-05)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.4-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.4/dwork-dhub-0.2.4-windows.zip) | `7f37ee32d70c38e984db43c3c8ee139d3efe35df1b2a8a7def3fa127da42b060` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.4-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.4/dwork-dhub-0.2.4-macos.pkg) | `eb209cbd0fc5ae8efc964f796d93d6f21c47755d635bad7afd586b35f892bf66` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.4-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.4/dwork-dhub-0.2.4-linux.deb) | `b0f85748fc796422500c7d1af858fe0496cf9e0bd5fb793eb47d44e47617f9b3` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.4-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.4/dwork-dhub-0.2.4-linux-arm64.deb) | `dd60d21b11fd7b440923149fdec344771a6ec11d80d8397159ad812e69dcde8b` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

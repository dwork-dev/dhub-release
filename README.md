# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.11** (released 2026-10-10)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.11-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.11/dwork-dhub-0.2.11-windows.zip) | `4c28993db21055015699a8fc870610077b7b4853f3925dcc537b9b4ad174ed39` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.11-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.11/dwork-dhub-0.2.11-macos.pkg) | `3447f965482e411a45ecdb80c759587c18bf2e8e8c91c3b736179cfe587e2e4f` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.11-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.11/dwork-dhub-0.2.11-linux.deb) | `99f0742a51bae5e9afeedb6c6f758f0b213a5eeef20c1c575d6ce770bca952e2` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.11-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.11/dwork-dhub-0.2.11-linux-arm64.deb) | `3bd878101fa1ed6a019294470ef63e52006db8457e82d80164a417780c83feee` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

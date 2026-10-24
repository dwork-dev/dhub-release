# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.13** (released 2026-10-24)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.13-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.13/dwork-dhub-0.2.13-windows.zip) | `c1902db0819bd04d24bccda5eea2e58bcc7439f3efbaea29ee91dab91e721d35` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.13-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.13/dwork-dhub-0.2.13-macos.pkg) | `7ec480f633de4c8fe7aa7b40583d0304cb285b27f5a59547cbf06c328c219d5d` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.13-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.13/dwork-dhub-0.2.13-linux.deb) | `46e23c8589e77f16b54dfb3c9621c8e7ae3c72669e9b8f7bb15fb7c04892f762` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.13-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.13/dwork-dhub-0.2.13-linux-arm64.deb) | `ac165ab41ec7fba52c3c248c5a3d144abbe83442d4760a10de9be7cb610cd8e9` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

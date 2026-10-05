# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.6** (released 2026-10-05)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.6-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.6/dwork-dhub-0.2.6-windows.zip) | `f79cdcdc8a2383f81eddc00212b7b6c76f4dba1da1618bdbb668e1a25ce8239c` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.6-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.6/dwork-dhub-0.2.6-macos.pkg) | `653b6f57b24b5dfa1af5384440f73e8efb362ef6cbdf1f2ff5c77ab0b591cd9b` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.6-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.6/dwork-dhub-0.2.6-linux.deb) | `0ab8520798647cf82b6dec4eb9eb8d9aa073e4dda5283c4e48e4cf5510dfcd0f` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.6-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.6/dwork-dhub-0.2.6-linux-arm64.deb) | `6b95d0567c2cbeea6583fc561cf3778ab279aad8c12cd9009413c9fc1739e542` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

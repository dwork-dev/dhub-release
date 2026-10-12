# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.12** (released 2026-10-12)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.12-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.12/dwork-dhub-0.2.12-windows.zip) | `8f606ce424dad38590b8ff0c13192bbf9bcf4fac861127e94988d4cd3a24aef8` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.12-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.12/dwork-dhub-0.2.12-macos.pkg) | `06eea1e281116f0f9244018ebea5ec0ade546d58bc93c9597c80e4aee75bfb62` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.12-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.12/dwork-dhub-0.2.12-linux.deb) | `2664c644a2da96fea8d05aedfc5c99521e44ac5613bdde5c994e49b5faaa6b4a` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.12-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.12/dwork-dhub-0.2.12-linux-arm64.deb) | `1a4455e68cd28a9d964e7f6ef7c5770e0bdc50aa59efea7dfa5fc611654391d8` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.7** (released 2026-10-06)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.7-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.7/dwork-dhub-0.2.7-windows.zip) | `da778922623ed2d3b46c9fa32fda09a73ecfa638822994ffd14ae180e4b5f3ab` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.7-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.7/dwork-dhub-0.2.7-macos.pkg) | `7f044de49209ff6f99a62c67800007bd822a8f45a685f634839d5a28bbdee8d7` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.7-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.7/dwork-dhub-0.2.7-linux.deb) | `eb359d1525dfe2997cb87435d5a60c18ff0f726802416e41bb7ca912d979ff2a` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.7-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.7/dwork-dhub-0.2.7-linux-arm64.deb) | `1b762e41e705bacdf3656324bc9a8011827e8997f935c931f915ed21bcaccf43` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

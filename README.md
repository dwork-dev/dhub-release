# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.14** (released 2026-10-29)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.14-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.14/dwork-dhub-0.2.14-windows.zip) | `4dd59e35bd392ad7038589223e0be10678eed485ff8188d004660accfc5a450d` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.14-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.14/dwork-dhub-0.2.14-macos.pkg) | `fa0f2ef3b5defece304a9532c394202a7792fbff6a644cc7fea60b5555464cd5` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.14-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.14/dwork-dhub-0.2.14-linux.deb) | `6b0b0c8cc777af7b99282468af5a6b73ab0cef16c454c9f7ade0f0dc53c5a0a3` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.14-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.14/dwork-dhub-0.2.14-linux-arm64.deb) | `810e629e7c733e98eb7fcfee20eb03c2eed9521aeecd5bc4c41abcc5f546bb41` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

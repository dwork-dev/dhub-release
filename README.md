# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.19** (released 2026-11-03)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.19-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.19/dwork-dhub-0.2.19-windows.zip) | `47e540ab03efdccae8c18f82fdf41be4d57104b6d0edc0583d34b482be9d9893` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.19-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.19/dwork-dhub-0.2.19-macos.pkg) | `a9bae0d081e6f27aa560cd8927302bb891e97f9c05f665b3bc1660f1104f9136` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.19-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.19/dwork-dhub-0.2.19-linux.deb) | `064eda2e6587cfb90ace3295bd837a633ff8601089d6aaa94d64303bdf235b8b` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.19-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.19/dwork-dhub-0.2.19-linux-arm64.deb) | `ee7cfc19d4daa963790ab53258eb1e965ef9341941f7cb213ea63c0eb832e629` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

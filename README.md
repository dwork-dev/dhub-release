# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.10** (released 2026-10-10)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.10-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.10/dwork-dhub-0.2.10-windows.zip) | `cbed9c356baf2125c267cc41fbd3861479f7fdb4a5d239b00a97cbc14cffb413` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.10-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.10/dwork-dhub-0.2.10-macos.pkg) | `0ea93ee4be0a95b60c3ac199dfd5eab7c1db77ab8adbe0afc7833e35019129f3` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.10-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.10/dwork-dhub-0.2.10-linux.deb) | `8e12a886b0921cfd6f1f4f3c8f47d24f420a2920752c1fc5c6818656a62809a0` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.10-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.10/dwork-dhub-0.2.10-linux-arm64.deb) | `356d5d4744fbfd9a207e992104039e6a85e1d62ecb349a60897fd32493782d8b` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

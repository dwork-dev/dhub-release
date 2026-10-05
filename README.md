# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.3** (released 2026-10-05)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| Windows 10/11 (64-bit) | [`dwork-dhub-0.2.3-windows.zip`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.3/dwork-dhub-0.2.3-windows.zip) | `6c9c4624f941cdcc57b1f9bac2c3b797bfb9b27e1fed1d5fcbf1edfa67ba9b81` |
| macOS (Apple Silicon) | [`dwork-dhub-0.2.3-macos.pkg`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.3/dwork-dhub-0.2.3-macos.pkg) | `ac86eeb72c94288a0a3aa22ff0885cb718c8bf02aa5ff8cb1de39516061e1b29` |
| Linux 64-bit (x86_64, .deb) | [`dwork-dhub-0.2.3-linux.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.3/dwork-dhub-0.2.3-linux.deb) | `1ab109bdbaf5ae3deaa098ffcb547501554918707309fdf44be57ccfc6d6934c` |
| Linux ARM 64-bit (.deb) | [`dwork-dhub-0.2.3-linux-arm64.deb`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.3/dwork-dhub-0.2.3-linux-arm64.deb) | `abea7cda5e6ca2964ccc414ff3b9072edc88c02446819fa877c13b90104947be` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

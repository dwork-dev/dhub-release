# DHub release

Public download point for **DHub**, the small background program that connects attendance terminals on a
local network to DWork. This repository holds only the download page and the release packages — no source code.

- Download page: https://dwork-dev.github.io/dhub-release/
- Current version: **0.2.1** (released 2026-10-02)
- Code-signed: no — your OS will warn on first run; see HUONG-DAN-CAI-DAT.txt in the package

| Platform | Package | SHA-256 |
|---|---|---|
| macOS (Apple Silicon) | [`dwork-dhub-0.2.1-macos.tar.gz`](https://github.com/dwork-dev/dhub-release/releases/download/v0.2.1/dwork-dhub-0.2.1-macos.tar.gz) | `62b9096322ea94f7344a1ca4b760c014570600f736412beb1ba253b391e55a24` |

Verify a download: `shasum -a 256 <file>` (macOS/Linux) or `certutil -hashfile <file> SHA256` (Windows) must print
the SHA-256 above. Do not install a DHub package obtained from anywhere else.

This repository is published by a script; changes made here by hand are overwritten on the next release.

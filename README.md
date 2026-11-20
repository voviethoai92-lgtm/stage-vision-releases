# stage-vision-releases
STAGE VISION 3D binaries, signed update metadata, signed payment configuration and public documentation.

- `channels/windows-stable/latest.json` — Windows Stable update feed (Tauri updater, signed artifacts on GitHub Releases).
- `payment/payment.json` — signed payment configuration shown as a VietQR code in the app.
- Releases are tagged `windows-vX.Y.Z` and contain the customer installer, its updater signature, `SHA256SUMS.txt` and `INSTALL_VI.md`.

This repository contains public release material only; no application source, signing keys, issuer tool, customer licences, ledgers or backups.

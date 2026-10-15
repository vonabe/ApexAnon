# ApexAnon VPN

VPN client for Windows. This repository distributes installers and automatic updates.

## Download

[Download the latest version](https://github.com/vonabe/ApexAnon/releases/latest)

Download the `ApexAnon-VPN_*_x64-setup.exe` asset. No certificate import is required.
The installer requires administrator permission. Windows may show a SmartScreen
warning because these installers do not yet have an Authenticode certificate.

## Updates

The EXE edition checks for updates in the background. Once downloaded, use
**Update and restart**, or install automatically on the next application launch.
The app verifies both the release manifest and installer signatures, and stops
the VPN before installation. MSIX editions do not use this update channel.

The `.sig`, `latest.json` and `latest.json.sig` files are used by the updater;
users only need to download the EXE installer.

Do not run the old MSIX edition and the EXE edition at the same time.

## License

Original ApexAnon code, interface and branding are proprietary. Official binaries
may be installed and used under the [ApexAnon Proprietary License](LICENSE).
Modification, repackaging, redistribution and presenting ApexAnon materials as
your own project require prior written permission, subject to applicable law
and the third-party license exceptions stated in that license.

Third-party components retain their own licenses, including sing-box (GPL)
and Xray-core (MPL). See [Third-party notices](THIRD_PARTY_NOTICES.md).
The proprietary license does not override those rights or source obligations.

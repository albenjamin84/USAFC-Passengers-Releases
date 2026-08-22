# USA Flight Club Passengers — Releases

![USA Flight Club Passengers release channel](assets/readme/release-banner.png)

> Official public installer, automatic-update, and release-notes channel for **USA Flight Club Passengers**.

## About this repository

This repository publishes signed release packages and update metadata for USA Flight Club Passengers. The application source code, private services, and operational integrations are maintained in private repositories and are **not** distributed here.

## Download and install

1. Open [Releases](../../releases).
2. Download the current `USAFlightClubPassengers-Setup.exe` asset.
3. Verify its SHA-256 checksum against the release notes.
4. Run the installer. Windows may show publisher/reputation prompts for a new release; only proceed when the download is from this official repository and the checksum matches.

The installer creates the application under `C:\Program Files\USA Flight Club Passengers\`. User data is kept under `%AppData%\USAFlightClubPassengers\`.

## Updates

The desktop application checks this official release channel for verified updates. Update packages must be signed and accompanied by SHA-256 checksums. Never install a package from a fork, mirror, or unsolicited link.

## Release contents

Each production release contains:

- Installer (`USAFlightClubPassengers-Setup.exe`)
- SHA-256 checksum file
- Versioned release notes
- Upgrade and rollback guidance when applicable

## Support and security

- Product support: open a GitHub issue using the appropriate template.
- Security vulnerabilities: follow [SECURITY.md](SECURITY.md). Do not post vulnerabilities in public issues.
- Privacy and data practices: see [PRIVACY.md](PRIVACY.md).

## Status

USA Flight Club Passengers is in active development. A GitHub release is the authoritative statement of downloadable build availability and functionality.

---

Copyright © 2026 USA Flight Club. All rights reserved. USA Flight Club Passengers is proprietary software.

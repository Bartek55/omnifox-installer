# OmniFox Installer

Official public download and release repository for OmniFox.

> No public installer has been released yet. Until a signed release appears on
> this repository's Releases page, do not trust downloads claiming to be an
> official OmniFox installer.

## Installation profiles

OmniFox uses one Smart Installer. During installation, you can choose:

- **Full** — the complete OmniFox experience, including local AI components.
- **Lite** — reduced download and storage requirements.
- **Browser-only** — the browser without optional local AI models.

The installer recommends a profile after checking the device, but the final
choice remains yours. Profiles can be changed later without deleting browser
profiles, bookmarks, passwords, history, settings, or other user data.

## Supported systems

The first public installer will target 64-bit Windows. Signed and notarized
macOS packages and signed Linux DEB/RPM packages will follow after they pass
their platform release gates.

Exact minimum operating-system, memory, storage, and architecture requirements
will be published with each release.

## Safe downloads

Official installers are published only through:

- this repository's **GitHub Releases**
- <https://omnifox.app/download>
- OmniFox update endpoints under `omnifox.app`
- large signed component downloads from `cdn.omnifox.app`

Each release will include signed manifests and SHA-256 checksums. Do not install
files from mirrors, advertisements, direct messages, or unofficial repositories.

## Updates and privacy

OmniFox checks signed update manifests over HTTPS. Updates must preserve user
profiles and support recovery if installation fails. Installing or updating
OmniFox does not require a Google account, payment method, telemetry consent, or
Google services.

Bug reports and diagnostic attachments are never submitted without user
action. Users can review the information offered for submission.

## Support

- Installation and update problems: `support@omnifox.app`
- Product bugs: `bugs@omnifox.app`
- Abuse or unsafe downloads: `report@omnifox.app`
- Security vulnerabilities: see [SECURITY.md](SECURITY.md)

Please do not include passwords, API keys, private browsing content, or other
sensitive information in public GitHub issues.

## Repository scope

This repository contains public release assets and user-facing release
documentation. OmniFox's private source code, development history, build
infrastructure, signing keys, and service credentials are not published here.


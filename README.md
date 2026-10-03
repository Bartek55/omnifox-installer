# OmniFox Installer

Official public download and release repository for OmniFox.

> No public installer has been released yet. Until a signed release appears on
> this repository's Releases page, do not trust downloads claiming to be an
> official OmniFox installer.

## Installation profiles

OmniFox uses one Smart Installer per supported operating system. During setup,
you can choose:

- **Full** — the complete OmniFox experience, including OmniFox's own local AI
  models.
- **Lite** — a smaller download that uses a local AI runtime you already have,
  such as Ollama or LM Studio. You can upgrade to Full later.

OmniFox is a browser with local AI, so every installation includes a local AI
profile. A computer with less than 8 GB of memory cannot run OmniFox's smallest
model, and setup will not continue on it.

The installer recommends a profile after checking the device, but the final
choice remains yours. Profiles can be changed later without deleting browser
profiles, bookmarks, passwords, history, settings, or other user data.

## Supported systems

OmniFox is being prepared for:

- **Windows 10 and Windows 11, 64-bit (x64)** — Intel and AMD processors
- **macOS 12 or later on Apple Silicon** (M1 or newer)

Windows releases will be signed, and macOS releases will be signed and
notarized, before they appear here. Intel-based Macs and Windows on ARM are not
supported at this time. Linux packages are planned for later.

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


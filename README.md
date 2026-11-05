# Star Defender Workshop — Windows releases

This repository is the **public binary-distribution channel** for Star Defender Workshop. It is separate from the private source repository.

Only Windows installer executables, checksums, and the `latest.json` update manifest belong here. **No source code, project files, credentials, or private game assets should be published to this repository.**

## Install and update

Once the first Windows release is published, download `StarDefenderWorkshopSetup_<version>.exe` from [Releases](../../releases). The Workshop desktop app checks the latest release at:

`https://github.com/tschiffbauer/star-defender-workshop-releases/releases/latest/download/latest.json`

The published manifest includes the installer version, size, HTTPS download URL, and SHA-256 digest. The app validates these before running the installer.

## Release publishing

The Windows installer is built in the private development repository using GitHub Actions and can be published here with a fine-grained repository-scoped token kept only in the development repository's GitHub Actions secrets.

The release channel is **not yet active until a release with the installer and `latest.json` has been published and verified.**

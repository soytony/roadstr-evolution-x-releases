# Evolution X for Moto Edge 70 / Moto X70 Air

Unofficial Evolution X releases for the Motorola Moto Edge 70 / Moto X70 Air
(codename: `roadstr`).

This project is not affiliated with Motorola or the Evolution X project.

## Releases

Find downloads, checksums, release notes, compatibility details, and installation
instructions on the repository's [Releases](../../releases) page.
Fastboot bundles are hosted in the [SourceForge Evolution X download
folder](https://sourceforge.net/projects/roadstr-custom-os/files/EvolutionX/).

## Installation

1. Back up important data and unlock the bootloader.
2. Read the selected release's installation guide and compatibility requirements.
3. Download the complete fastboot ZIP and verify its published SHA-256 checksum.
4. Extract the bundle and run `flash_all.sh` on Linux/macOS or `flash_all.bat`
   on Windows, following the release-specific instructions and installer prompts.

The bundle includes the required Motorola base firmware and flashes it before
Android. Do not mix firmware versions or relock the bootloader. Data-wipe policy
and known limitations are documented with each release.

## Google Apps

Google services and apps are included. Do not flash a separate GApps package.

## Source and Issues

- [Evolution X](https://github.com/Evolution-X)

Report reproducible issues through this repository's [issue tracker](../../issues).
Include the release version, device variant, clean or dirty installation status,
steps to reproduce, and relevant logs. Remove personal data, account details,
and device serial numbers before posting.

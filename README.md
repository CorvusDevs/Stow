# Stow

<p align="center">
  <img src="docs/assets/stow-icon.png" width="128" alt="Stow app icon">
</p>

<p align="center"><strong>Zip, unzip, and archive with care.</strong></p>

<p align="center">
  <a href="https://corvusdevs.github.io/Stow/">Website</a> ·
  <a href="https://corvusdevs.github.io/Stow/changelog.html">Updates</a> ·
  <a href="https://corvusdevs.github.io/Stow/support.html">Support</a> ·
  <a href="https://corvusdevs.github.io/Stow/privacy.html">Privacy</a> ·
  <a href="https://apps.apple.com/app/id6801190003">App Store</a>
</p>

Stow is a privacy-first archive utility for Mac, iPhone, and iPad. It packs, unpacks, browses, encrypts, splits, and verifies archives without an account, tracking, advertising, or file uploads.

## What it does

- Create ZIP, 7-Zip, TAR, and common compressed TAR archives.
- Open a broad range of archive formats.
- Browse an archive on Mac before extracting anything.
- Limit archive expansion and item counts to reduce the risk from zip bombs.
- Create AES-256 encrypted ZIP and 7z archives. 7z can hide file names too.
- Queue work, verify archives with SHA-256 checksums, and split large archives into smaller volumes.
- Integrate with Finder on Mac for quick compression and extraction.
- Pack and unpack files from the Files app on iPhone and iPad.

## Platform focus

The Mac app is the full archive workstation. iPhone and iPad are deliberately focused companions for packing and unpacking files from the Files app. Mobile does not claim feature parity with Mac.

## Safer extraction on Mac

Before extracted files reach their destination, Stow checks archive paths, symlink targets, declared sizes, streamed output, and item counts. Suspicious archives are stopped in a temporary staging area. These limits reduce the risk from decompression bombs, commonly called zip bombs, without claiming that any archive utility can recognize every malicious file.

## Support

For help, email [corvusdevs@outlook.com](mailto:corvusdevs@outlook.com). Please include your Stow version, operating system version, archive format, and the error you saw. Do not send passwords or sensitive archive contents.

## Privacy

Stow does not collect, track, sell, or transmit your personal data. Read the full [privacy policy](https://corvusdevs.github.io/Stow/privacy.html).

## Third-party notices

See [third-party notices](docs/third-party-notices.md) for licenses and attribution.

# KhataRasoi POS releases

This repository holds only the **published installers** of KhataRasoi POS, their checksums and the update feeds that the desktop app reads. It contains no source code.

- **Downloads and the version on offer:** <https://khatarasoi.in/download/>
- **Support:** support@khatarasoi.in · +91 6026013891

## What each release contains
- Installers for the platforms listed in that release. A platform that is not listed has no installer for that version.
- `SHA256SUMS`: the SHA-256 of every installer.
- `latest*.yml`: update feeds for the desktop app's built-in updater.
- `RELEASE_NOTES.md`: what changed.

Each release says whether its Windows installers are code-signed and whether its macOS disk images are signed and notarized by Apple.

## Verify a download
Compare the SHA-256 of the file you downloaded with the one in `SHA256SUMS` and on the download page:
- macOS or Linux: `shasum -a 256 <file>`
- Windows: `Get-FileHash <file> -Algorithm SHA256`

Do not install a file whose checksum does not match. Email support@khatarasoi.in instead.

KhataRasoi is proprietary software. Installing it does not grant any rights to its source code.

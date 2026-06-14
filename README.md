# Icon Hook LSP

![Android](https://img.shields.io/badge/Android-8%2B-3DDC84)
![LSPosed/Xposed](https://img.shields.io/badge/LSPosed%20%2F%20Xposed-module-555555)
![Public Release](https://img.shields.io/badge/Public%20Release-APK-blue)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)

Icon Hook LSP is an Android LSPosed/Xposed module for user-configurable app label and icon display replacement.

This repository is a public release and showcase repository. It is intended to provide project information, public APK downloads, release notes, checksums, and contact guidance. The private development source tree, complete build chain, internal implementation, and adaptation details are not published here.

## Features

- Configure replacement display names for selected installed apps.
- Configure replacement icons for selected installed apps.
- Manage enabled and disabled replacement rules from the companion app.
- Apply replacement behavior across supported Android display surfaces.
- Keep rules local to the device.

## Requirements

- Android device with root access.
- LSPosed or a compatible Xposed runtime.
- A supported Android version and ROM environment.
- Basic familiarity with enabling modules and selecting scopes in LSPosed/Xposed.

## Download

Download the latest public APK from the GitHub Releases page:

<https://github.com/ethansrz9/icon-hook-lsp/releases>

Checksums for public release artifacts are listed in `SHA256SUMS.txt` when available.

## Usage

1. Download the latest APK from GitHub Releases.
2. Install the APK on the device.
3. Enable the module in LSPosed/Xposed.
4. Select the recommended scopes shown by the module.
5. Open Icon Hook LSP and create replacement rules for the apps you want to customize.
6. Restart, reboot, or reload the relevant Android UI process if changes do not appear immediately.

## Notes

- This is a release-oriented public repository.
- The complete private build environment is not included.
- Internal implementation details, private adaptation notes, and full source code are not published.
- This repository does not provide instructions for reproducing the private module implementation.
- Public APK builds are distributed through GitHub Releases.

## License

All rights reserved. See `LICENSE` for details.

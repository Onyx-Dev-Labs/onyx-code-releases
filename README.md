# Onyx Code releases

Public installers and update metadata for Onyx Code. This repository does not contain the product source repository or user data.

## Download

Open the [latest release](https://github.com/Onyx-Dev-Labs/onyx-code-releases/releases/latest) and download the Apple Silicon `.dmg` under Assets. The automatically generated source ZIP contains only this distribution repository; it is not an installer.

Quit Onyx after its active work finishes, open the DMG, and replace Onyx Code (Alpha) in Applications. Keep the existing application data to retain conversations and settings.

These builds are Developer ID signed but are not notarized. If macOS blocks opening the application, use System Settings > Privacy & Security > Open Anyway. Do not disable Gatekeeper globally.

## Updates

Version 0.1.2 introduces the public HTTPS update feed. Earlier versions require a one-time installation of this transition build. Afterward, use Help > Check for Updates. Access to this feed does not require a GitHub login or Tailscale.

Updates require an explicit install action. Publishing a release does not force an application restart. Finish active work before installing an update.

The stable Apple Silicon update manifest is:

`https://github.com/Onyx-Dev-Labs/onyx-code-releases/releases/latest/download/onyx-alpha-latest-mac.yml`

Installer downloads do not grant access to Hermes agents, development environments, provider accounts, or private source code. Those connections retain their own authentication and network requirements.

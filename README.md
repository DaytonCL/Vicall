<p align="center">
  <img src="assets/vicall-app-icon.png" width="120" alt="Vicall icon">
</p>

<h1 align="center">Vicall</h1>

<p align="center">
  <strong>Private P2P calls with high-quality audio and explicit media control.</strong>
</p>

<p align="center">
  <a href="https://github.com/DaytonCL/Vicall/releases/latest">Download for Windows</a>
  ·
  <a href="https://github.com/DaytonCL/Vicall/issues">Report an issue</a>
</p>

> **Public distribution repository.** Vicall's source code is maintained privately. This repository contains product information and official release binaries only.

<p align="center">
  <img src="assets/vicall-home.png" width="100%" alt="Vicall desktop interface">
</p>

## Download

The current public Windows build is available from **GitHub Releases**:

**[Download the latest Vicall release →](https://github.com/DaytonCL/Vicall/releases/latest)**

| Platform | Availability |
| --- | --- |
| Windows x64 | Available in Releases |
| Android | Not published in this repository |
| iOS | Not published in this repository |

## What Vicall is

Vicall is a direct P2P calling app built around a simple idea: keep the media path private and make audio behavior explicit instead of hiding it behind automatic processing.

- Direct device-to-device audio, video and data when a reachable P2P route exists.
- 48 kHz stereo audio with uncompressed PCM or high-bitrate Opus modes.
- Optional echo cancellation and full voice processing instead of forced processing.
- Separate camera and screen-sharing sources.
- Explicit microphone, camera, output and screen ownership across paired devices.
- Friends, direct messages, file transfer and call invitations.
- Shared mini-apps that run inside the call session.

## Network model

Vicall is intentionally direct-first. Call media is not routed through a central media server.

Audio, video and data use encrypted P2P sessions. Signaling is used to establish the connection, while media travels between the participants' devices whenever a direct route is available.

Because Vicall does not rely on a TURN or SFU media relay, some network combinations may require a shared VPN or another reachable direct route.

## Installation on Windows

1. Open the [latest release](https://github.com/DaytonCL/Vicall/releases/latest).
2. Download the Windows installer from **Assets**.
3. Run the installer and launch Vicall.

Release notes and file integrity information are published with each release.

## Repository model

This repository is intentionally **binary-only** from a product perspective:

- no application source code;
- no private development history;
- no build scripts or internal configuration;
- public documentation and screenshots live in git;
- installers are distributed through GitHub Releases.

Development happens in a separate private repository.

## Feedback

Use [GitHub Issues](https://github.com/DaytonCL/Vicall/issues) for reproducible bugs and public feedback. Please avoid posting room links, private identifiers, personal files or other sensitive data in issues.

---

**Vicall 0.6.6** · Windows x64

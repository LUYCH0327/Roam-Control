<p align="center">
  <img src="Documentation/Images/RoamControl-AppIcon-v2-source.png" width="128" height="128" alt="Roam Control app icon">
</p>

<h1 align="center">Roam Control</h1>

<p align="center">
  Choose, test and move an iPhone's reported location from one clean Apple Maps interface.
</p>

<p align="center">
  <strong>Current release:</strong> 0.9.4 Build 74 · <strong>Requires:</strong> iOS 27+
</p>

<p align="center">
  <img src="https://img.shields.io/badge/iOS-27%2B-blue" alt="iOS 27+">
  <img src="https://img.shields.io/badge/UI-SwiftUI-orange" alt="SwiftUI">
  <img src="https://img.shields.io/badge/Current-0.9.4-lightgrey" alt="Current release 0.9.4">
  <img src="https://img.shields.io/badge/License-PolyForm%20NC%201.0.0-blue" alt="PolyForm Noncommercial 1.0.0">
</p>

## About

Roam Control is an iPhone app for location-based development, quality assurance and responsible personal testing on a device you own and control.

It supports fixed reported locations, simulated walking routes, favourites, history, on-device pairing and guided LocalDevVPN-compatible sessions.

Roam Control is distributed as a prebuilt IPA. The application source code is not publicly distributed.

## Screenshots

<p align="center">
  <img src="Documentation/Images/README/roam-welcome.png" width="240" alt="Roam Control welcome screen">
  <img src="Documentation/Images/README/roam-fixed-location.png" width="240" alt="Selecting a fixed location in London">
  <img src="Documentation/Images/README/roam-walking-preview.png" width="240" alt="Walking route preview">
</p>

<p align="center">
  <sub>Welcome · Fixed location · Walking route</sub>
</p>

<p align="center">
  <img src="Documentation/Images/README/roam-manual-route.png" width="240" alt="Building a manual walking route">
  <img src="Documentation/Images/README/roam-connection-health.png" width="240" alt="Connection Health and Manual Diagnostics">
</p>

<p align="center">
  <sub>Manual route drawing · Connection Health</sub>
</p>

## Features

- Search for places, enter coordinates or select a position on the map.
- Start and update a fixed reported location.
- Preview and simulate Apple Maps walking routes, or build routes manually with point-by-point and freehand drawing.
- Pause, resume, reverse or redirect an active walk.
- Save favourites and revisit recent locations.
- Restore the iPhone's real location when testing is finished.
- Recover from interrupted fixed or walking sessions.
- Guided LocalDevVPN setup for Wi-Fi and mobile-data use.
- Light, dark and automatic appearance.
- Dynamic Type, VoiceOver and Reduce Motion support.

## Install

Roam Control is not distributed through the App Store or TestFlight.

Download the IPA attached to the current GitHub Release and install it using SideStore.

Read the [Installation Guide](Documentation/Installation.md) before installing.

Only download Roam Control from the official GitHub repository. Unofficial mirrors, modified builds and redistributed copies are not authorised.

## Documentation

- [Installation](Documentation/Installation.md)
- [User Guide](Documentation/UserGuide.md)
- [Using a Personal VPN](Documentation/PersonalVPN.md)
- [VPN Compatibility](Documentation/VPNCompatibility.md)
- [Advanced: Self-hosted IKEv2 on Linux](Documentation/SelfHostedIKEv2.md)
- [Current Release](Documentation/CurrentRelease.md)
- [Release History](Documentation/ReleaseHistory.md)
- [Privacy](Documentation/Privacy.md)
- [Responsible Use](Documentation/ResponsibleUse.md)
- [Security Policy](SECURITY.md)

## Privacy

Locations, searches, favourites, history, walking routes and pairing records remain on the iPhone.

Anonymous usage statistics are optional and off by default. See the [Privacy Policy](Documentation/Privacy.md) for the exact information that may be reported when sharing is enabled.

## Responsible use

Roam Control is intended for development and testing on an iPhone you own and control.

Location simulation can affect every app that uses the iPhone's reported position. Restore the real location before using navigation, emergency, safety, transport or location-sharing features.

See [Responsible Use](Documentation/ResponsibleUse.md).

## Support and feedback

Bug reports, feature requests, testing results and technical findings are welcome through GitHub Issues.

Roam Control is maintainer-developed and is not accepting pull requests or unsolicited code contributions.

For casual help, beta discussion and feature ideas, join the Roam Control Discord:

https://discord.gg/fJrNvQ2Vdh

For security-sensitive reports, use GitHub Security Advisories.

## Releases

Roam Control normally keeps downloadable IPA assets for the current stable release and, where appropriate, the immediately previous stable release.

Older GitHub Releases may remain visible as historical records after their downloadable assets have been retired.

## Licence and copyright

Roam Control is proprietary software.

Copyright © 2026 Sean Howarth. All rights reserved.

The public IPA may be downloaded and used personally subject to the terms in [LICENSE](LICENSE). Redistribution, modification, repackaging, mirroring and unofficial releases are not permitted without prior written permission.

Historical source code that was previously published under other licences remains governed by the licence applicable to the specific version when it was published. Those historical grants are not revoked by the current distribution model.

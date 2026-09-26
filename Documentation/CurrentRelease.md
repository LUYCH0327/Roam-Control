# Roam Control 0.9.4

Build 74, released 26 September 2026.

Roam Control 0.9.4 is the current public release for testing an iPhone's reported location from a clean Apple Maps interface.

## Before installing

- Requires iOS 27 or newer.
- Requires Developer Mode and LocalDevVPN.
- This is an unsigned IPA. SideStore signs it with the user's own Apple account.
- Intended only for development, quality assurance and responsible testing on a device the user owns and controls.

Read the [installation guide](Installation.md), [privacy explanation](Privacy.md) and [responsible-use policy](ResponsibleUse.md) before using it.

## Download

Download `RoamControl-0.9.4-build74.ipa` from the [Roam Control 0.9.4 release](https://github.com/seanhowarthdev/Roam-Control/releases/tag/v0.9.4).

SHA-256:

`b55bf4bf6a509dd02731a6e4e97253724857a72cc31085571bd6eda1e5d0ad20`

## Highlights

### Data and migration

- Added Backup & Restore for favourites, history and supported app preferences.
- Backups can restore appearance, map style and location compatibility settings.
- Added preparation for the one-time Roam Control 0.9.5 migration.

### Freehand routes and walking

- Added freehand route drawing alongside point-by-point route creation.
- Added Points and Freehand drawing modes.
- Draw with one finger while using two fingers to pan, zoom or rotate the map.
- Undo freehand routes one stroke at a time.
- Redesigned walking and route-planning controls into a more compact layout.
- Added collapsible location and Route Planning cards.
- Added clearer Start and End route markers.
- Kept Pause, Resume and Stop & Restore readily available during active walks.
- Refined route preview, walking progress and map behaviour.

### Location compatibility

- Added automatic coordinate correction for searched and selected locations in Mainland China.
- Added Automatic, Off and Force Correction compatibility modes.
- Correction is applied to the simulated device location while the selected map marker stays where the user chose it.
- Manually entered coordinates are not automatically changed.

### Sessions, updates and VPNs

- Improved Stop & Restore guidance and real-location reacquisition messaging.
- Stable update checks now ignore GitHub drafts and prereleases.
- Updated Connection Health guidance for compatible Personal VPNs and Device VPN conflicts.
- Restored an immutable packaged build timestamp so SideStore re-signing does not change the displayed build time.

## Backup & Restore

Backup & Restore is available from Settings.

Backups include favourites, history, appearance, map style and location compatibility preferences.

Pairing records, analytics consent, analytics identity, active-session recovery data and diagnostics are deliberately not included.

Roam Control 0.9.5 will use a new app identifier. Users upgrading from 0.9.4 should create a fresh backup before moving to 0.9.5 and will need to pair the iPhone again afterward.

## Distribution constraints

SideStore and free Apple accounts are subject to Apple's app-count and seven-day refresh limits. Pairing and location sessions require a physical iPhone.

Please report ordinary bugs with the issue template and security problems through a private GitHub security advisory.

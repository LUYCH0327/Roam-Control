# Installation

Roam Control is not distributed through the App Store or TestFlight. Public beta builds are supplied as unsigned IPA files for users to sign with their own Apple account.

## Requirements

- An iPhone running iOS 27 or newer.
- Developer Mode enabled under **Settings → Privacy & Security**.
- [LocalDevVPN](https://apps.apple.com/app/localdevvpn/id6755608044) installed on the iPhone.
- SideStore for a standalone install, or LiveContainer for a contained install.

## Install with SideStore

1. Download the IPA attached to the matching GitHub Release. Do not download an IPA from an untrusted mirror.
2. In SideStore, tap **+** and choose the downloaded IPA.
3. Allow SideStore to sign and install Roam Control with your Apple account.
4. Open Roam Control and complete its introduction and device-pairing flow.
5. Open LocalDevVPN and enable its local tunnel before starting a location.

Free Apple accounts normally require sideloaded apps to be refreshed within seven days and limit the number of simultaneously active apps/App IDs. These are Apple signing limits, not Roam Control subscriptions.

When updating, install the newer IPA over the existing copy. Deleting the app first also deletes its local settings and may require pairing again.


## Install with LiveContainer

Roam Control can also run through LiveContainer.

1. Download the IPA attached to the matching GitHub Release.
2. Import Roam Control into LiveContainer.
3. **Before launching Roam Control for the first time**, enable LiveContainer's local-notification compatibility option for that Roam Control instance:

   **LiveContainer → Apps → long-press Roam Control → App Settings → Fix Local Notifications → On**

4. Launch Roam Control and continue through first-time setup and pairing normally.
5. Open LocalDevVPN and enable its local tunnel before starting a location.

With **Fix Local Notifications** enabled, the pairing notification is delivered through LiveContainer. Tapping it returns to the correct Roam Control instance so pairing can continue normally.

Because LiveContainer relays the notification, it may show LiveContainer, sandbox or container-style details rather than looking exactly like a notification from a standalone Roam Control install. This is specific to the LiveContainer environment. SideStore installs are unaffected.

## Verify a release

Each GitHub Release publishes the IPA's SHA-256 checksum. On a Mac, calculate the checksum of the IPA you downloaded:

```sh
shasum -a 256 RoamControl-0.9.2-Beta3-build53.ipa
```

Compare the result with the SHA-256 value shown on the matching GitHub Release before installing it.

See the [user guide](UserGuide.md) for pairing and everyday operation.

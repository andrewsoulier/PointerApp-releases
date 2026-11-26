# PointerApp releases

Download builds of **PointerApp**, a macOS menu-bar app that puts an animated cartoon pointer (hands, sticks, an arrow, a little ship) over your cursor, with click animations and sound packs.

This repository only hosts the release downloads and the update feed (`appcast.xml`). The source code is private.

## Install

1. Open [Releases](https://github.com/andrewsoulier/PointerApp-releases/releases/latest) and download `PointerApp-<version>.zip`.
2. Unzip it and drag **PointerApp.app** into your **Applications** folder.
3. **First launch:** PointerApp isn't signed with an Apple Developer ID, so macOS will block a normal double-click. **Right-click (or Control-click) PointerApp.app and choose Open**, then click **Open** in the dialog. You only need to do this once. On newer macOS versions you may instead need to go to **System Settings > Privacy & Security** and click **Open Anyway**.
4. PointerApp lives in the menu bar (no Dock icon). Use the menu-bar icon for settings; press **⌃⌥P** to turn the pointer on or off.

Requires macOS 13 or later.

## Updates

PointerApp checks this repository's `appcast.xml` for new versions (Sparkle). Updates are signed with an EdDSA key, so the app only installs builds that were published here. You can check manually with **Check for Updates…** in the menu, or turn automatic checks on or off in **Settings > General**.

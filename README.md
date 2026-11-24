# OLIVER Windows

Android app that runs Windows (x86_64) `.exe` apps and games using Wine + Box64.
Based on [Winlator](https://github.com/brunodev85/winlator) (GPL-3.0), rebranded as OLIVER Windows.

## Build (GitHub Actions, phone only)
1. Upload this project to GitHub.
2. Open **Actions → Build OLIVER Windows APK → Run workflow**.
3. Download the APK from **Artifacts** when it finishes.

## Use
1. Open the app and wait for first-time setup.
2. Create a Container (Graphics: Turnip for Snapdragon, DXVK on).
3. Start the container, then **Start Menu → Run** and pick a `.exe`/`.msi`.

## Notes
- Package name is kept as `com.winlator` because Wine paths inside the root filesystem depend on it. Do not install alongside the original Winlator.
- License: GPL-3.0. Keep `LICENSE` and credit the original authors.

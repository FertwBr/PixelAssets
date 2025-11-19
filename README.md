# PixelAssets

This repository acts as a centralized Content Delivery Network (CDN) for **Pixel Compass** and **Pixel Pulse** Android applications.

It hosts static assets such as "What's New" images, banners, and other media resources that are fetched dynamically by the apps. This strategy allows for:
* **Reduced APK Size:** Large images are not bundled with the installation.
* **Dynamic Updates:** Assets can be updated without releasing a new app version on the Play Store.

## 📂 Directory Structure

The repository is organized by application to maintain a clean architecture:

```text
PixelAssets/
├── Compass/              # Assets for Pixel Compass
│   ├── whatsnew/         # Images for changelogs
│   └── ...
│
├── Pulse/                # Assets for Pixel Pulse
│   ├── whatsnew/
│   └── ...
│
└── README.md
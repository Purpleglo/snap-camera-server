# 👻 Snap Camera Server v3.2
An alternative self hosted solution for Snap Camera.  
It will let you continue to use Snapcamera with all Snapchat filters after the shutdown on January 25, 2023.

**This code is a fork of *jaku/SnapCameraPreservation* on steroids 💪** 
- ✔️ No previously backed up files or third party server required.
- ✔️ Access all Snap Lenses from **lens.snapchat.com** without restrictions.
- ✔️ Import Lenses from local application cache e.g. `AppData\Local\Snap\Snap Camera\cache\lenses`.
- ✔️ All files will be stored inside a Docker Volume (e.g. on your local machine).
- ✔️ Works 100% on Windows and Mac OS without missing Lenses.

You get the full decentralized control and you can use *Snap Camera* until Doomsday.

See the [📋 Changelog](docs/CHANGELOG.md) for a full list of changes and features.

## ⚠️ Pre-Requirements
This server requires Docker and OpenSSL and maybe 5 to 10 minutes of your time ⏲️
- [🐋 Docker](https://www.docker.com/)
- [🔐 OpenSSL](https://www.openssl.org/) (Download from [slproweb.com](https://slproweb.com/products/Win32OpenSSL.html) as Windows user)

*The client application is required to apply the filters to your webcam ([Download Snap Camera](https://github.com/ptrumpis/snap-camera-server/discussions/6))*

## 🚀 Getting Started
1. [📥 Download the latest release](https://github.com/ptrumpis/snap-camera-server/releases/latest)
2. [🛠️ Complete the configuration](docs/CONFIGURATION.md)
3. [📖 Read the Server Wiki](https://github.com/ptrumpis/snap-camera-server/wiki)

There are also step by step video guides for [📺 Windows](https://www.youtube.com/watch?v=bcsjvWHUr7c) and [📺 Mac OS](https://www.youtube.com/watch?v=b2ILHJaD1T4) available.  
If you want to upgrade an existing server version to a newer version, have a look at:
- [Upgrade v2.x to v3.x](docs/UPGRADING_v3.md)

## 💯 Advanced Features
### 📤 Snap Camera Cache Import 
You can import your local cached lenses through this online interface [Snap Lens Cache Import](https://ptrumpis.github.io/snap-lens-cache-import/)  
Watch the [📺 Re-Import Cache Video Guide](https://www.youtube.com/watch?v=alo49et3QxY) if you need help.

### 🌐 Web Lens Download
All Snap Lenses are still available for download at **https://lens.snapchat.com** (hidden from view).  
You need to apply a special [Snap Camera Signature Patch](https://ptrumpis.github.io/snap-camera-signature-patch/) to your `Snap Camera.exe` to get access to these web lenses.

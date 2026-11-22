<div align="center">

# CobbleLauncher

**Mods, worlds and packs for Minecraft Bedrock on Android**

[![Android](https://img.shields.io/badge/Android-9.0%2B-green?style=flat-square&logo=android)](https://www.android.com/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/Xrezt-Hub/LeviLauncher-Android?style=flat-square&color=yellow)](https://github.com/Xrezt-Hub/LeviLauncher-Android)
[![Issues](https://img.shields.io/github/issues/Xrezt-Hub/LeviLauncher-Android?style=flat-square&color=red)](https://github.com/Xrezt-Hub/LeviLauncher-Android/issues)

</div>

---

## About

CobbleLauncher is a lightweight Android launcher for Minecraft Bedrock Edition. It runs alongside your Google Play copy of Minecraft and lets you manage game versions, mods, worlds and packs in one place.

CobbleLauncher is a fork of [LeviLauncher-Android](https://github.com/LiteLDev/LeviLauncher-Android) by LeviMC, used under the Apache License 2.0.

## Features

- **Launch** – start your installed Minecraft Bedrock in one tap
- **Mods** – native mod loader with a package browser and installed-mods list
- **Worlds and packs** – manage worlds, resource packs and skin packs
- **Content download** – find content on CurseForge and add external mods
- **Instances** – keep separate game setups side by side
- **HUD tools** – zoom, FPS and CPS displays and more modules
- **Discord Rich Presence** – show launcher activity and Minecraft version on Discord

## Requirements

- Android 9.0 (API 28) or higher, ARM64 device
- Minecraft Bedrock 1.21.80 or later, installed from Google Play
- A licensed copy of Minecraft Bedrock (CobbleLauncher does not include the game)
- At least 2 GB free storage (5 GB recommended)

## Install

1. Download the latest APK from the [Releases](https://github.com/Xrezt-Hub/LeviLauncher-Android/releases) page.
2. Open the APK and allow "Install unknown apps" for your browser or file manager when Android asks.
3. Install it, open CobbleLauncher and grant the permissions it requests.

## Build from source

Requires Git, Android Studio, JDK 21+, the Android SDK (API 28+) and the NDK with CMake.

```bash
git clone https://github.com/Xrezt-Hub/LeviLauncher-Android.git
cd LeviLauncher-Android
./gradlew assembleDebug
```

Optional settings:

| Setting | Where | Purpose |
|---|---|---|
| `curseforge.api_key` | `local.properties` | Enables CurseForge browsing |
| `application_id`, `large_image` | `discord.properties` | Discord Rich Presence app and image |

For GitHub Actions builds, add the `CURSEFORGE_API_KEY` secret in the repository settings.

## Disclaimer

CobbleLauncher is not an official Minecraft product and is not approved by or associated with Mojang or Microsoft. Use it only with a legitimate copy of the game and in line with Minecraft's terms of service. The authors are not responsible for bans or damages from its use.

## Credits

- **LeviMC** and the [contributors](https://github.com/LiteLDev/LeviLauncher-Android/graphs/contributors) of the original LeviLauncher-Android, on which this project is based
- Everyone behind the open-source libraries this launcher uses

## License

Licensed under the [Apache License 2.0](LICENSE). Keep the license file and the original copyright notices when you redistribute.

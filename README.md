<h1 align="center">
  <img loading="lazy" src="readme-res/banner.png"/>
</h1>
<p align="center">
  <a href="https://github.com"><img loading="lazy" src="https://shields.io"/></a>
  <a href="https://github.com"><img loading="lazy" src="https://shields.io"/></a>
  <a href="https://github.com"><img loading="lazy" src="https://shields.io"/></a>
  <a href="https://github.com"><img loading="lazy" src="https://shields.io"/></a>
</p>
<p align="center">LightROMUI is an ultra-lightweight, core-apps-only custom One UI firmware for Samsung Galaxy devices.</p>

<p align="center">
  <a href="https://github.com">📖 Wiki</a>
  <a href="https://github.com">📦 Releases</a>
  <a href="https://github.com">⚠ Issues</a>
</p>

# What is LightROMUI?
LightROMUI is a heavily stripped-down custom One UI firmware built for maximum speed, minimal RAM footprint, and improved battery life on Samsung Galaxy devices.

Built upon the ExtremeROM / UN1CA build system, LightROMUI removes non-essential Samsung bloatware, background telemetry, and redundant services—leaving only core system functionality and essential daily-driver apps out of the box.

LightROMUI supports devices using the Exynos 990 SoC (starting with the Galaxy S20 Ultra `z3s`).

Any form of contribution, suggestions, bug report or feature request for the project is welcome.

# Features
- Based on OneUI 7 Galaxy S24 FE firmware (via ExtremeROM / UN1CA base)
- **Ultra-Stripped Core-Only Setup:** Aggressive whitelist debloat removing non-essential system services, Bixby, AR Emoji, Game Launcher, and carrier bloat
- Heavily DeKnoxed
- Full SELinux Support
- Completely upstreamed kernels
- Adaptive color tone & Super HDR support
- Adaptive Brightness & Adaptive Refresh Rate support
- Full CSC support
- Multi-User & AppLock support
- EroFS partitions
- High end animations & Native/live blur support
- [BluetoothLibraryPatcher](https://github.com/3arthur6/BluetoothLibraryPatcher) included
- [KnoxPatch](https://github.com/salvogiangri/KnoxPatch) implemented in system frameworks
- Extra mods (Disable Secure Flag, OutDoor mode)
- Extra CSC features (Call recording, Network speed in status bar, 5GHz Hotspot)

# Bugs
See the <a href="https://github.com">⚠ Issues</a> tab

# Licensing
This project is licensed under the terms of the [GNU General Public License v3.0](LICENSE). External dependencies might be distributed under a different license, such as:
- [android-tools](https://github.com/nmeum/android-tools), licensed under the [Apache License 2.0](https://github.com/nmeum/android-tools/blob/master/LICENSE)
- [apktool](https://github.com/iBotPeaches/Apktool), licensed under the [Apache License 2.0](https://github.com/iBotPeaches/Apktool/blob/master/LICENSE.md)
- [erofs-utils](https://github.com/sekaiacg/erofs-utils/), dual license ([GPL-2.0](https://github.com/sekaiacg/erofs-utils/blob/dev/LICENSES/GPL-2.0), [Apache-2.0](https://github.com/sekaiacg/erofs-utils/blob/dev/LICENSES/Apache-2.0))
- [img2sdat](https://github.com/xpirt/img2sdat), licensed under the [MIT License](https://github.com/xpirt/img2sdat/blob/master/LICENSE)
- [platform_build](https://android.googlesource.com/platform/build/) (ext4_utils, f2fs_utils, signapk), licensed under the [Apache License 2.0](https://source.android.com/docs/setup/about/licenses)
- [smali](https://github.com/google/smali), [multiple licenses](https://github.com/google/smali/blob/main/third_party/NOTICE)

# Accountability
```cpp
#include <std_disclaimer.h>

/*
* Your warranty is now void.
*
* I am not responsible for bricked devices, dead SD cards,
* thermonuclear war, or you getting fired because the alarm app failed. Please
* do some research if you have any concerns about doing this to your device
* YOU are choosing to make these modifications, and if
* you point the finger at me for messing up your device, I will laugh at you.
*
* I am also not responsible for you getting in trouble for using any of the
* features in this ROM, including but not limited to Call Recording, secure
* flag removal etc.
*/
```

# Credits
A big thanks goes to the ExtremeROM and UN1CA teams and contributors whose foundational work makes LightROMUI possible:
- **[ExtremeXT](https://github.com/ExtremeXT)** for ExtremeROM Nexus and Exynos device/vendor bringup
- **[salvogiangri](https://github.com/salvogiangri)** for the UN1CA build system, OneUI patches, and general help and support
- **[Ocin4Ever](https://github.com/Ocin4Ever)** for smali help and advice
- **[Igor](https://github.com/BotchedRPR)** for porting guidance and support
- **[Halal Beef](https://github.com/halal-beef)** for lk3rd, testing and misc help
- **[Emad](https://github.com/emadhamid7)** for help with S10-specific fixes
- **[Duhan](https://github.com/duhansysl)** for vendor backports and fixes
- **[Anan](https://github.com/ananjaser1211)** for OneUI porting contributions
- **[PeterKnecht93](https://github.com/PeterKnecht93)** for smali and misc fixes
- **[tsn](https://github.com/tisenu100)** for smali fixes and advice
- **[Nguyen Long](https://github.com/LumiPlayground)** for misc fixes and support
- **[AlexFurina](https://github.com/AlexFurina)** for S10 specific fixes
- **[Luphaestus](https://github.com/Luphaestus)** for Note 20 specific fixes
- **[Yagzie](https://github.com/Yagzie)** for engmode and misc fixes
- **[Fred](https://github.com/xfwdrev)** for WFD, HDR10+, audiopolicy and more fixes
- **[Saad](https://github.com/saadelasfur)** for help with build system
- **[Vince](https://github.com/borbelyvince)** for help with kernel upstream
- **Nhat Vo** for Google Telemetry app removal
- **[Code Malaya](https://github.com/jomiejoshiro)** for SPen Air Actions
- **[Renox](https://github.com/renoxtv)** for overlay patches and testing
- **[Ksawlii](https://github.com/Ksawlii)** for updating the build system and FOD animation patch
- **[nalz0](https://github.com/nalz0)** for Multi-User support
- **[EndaDwagon](https://github.com/EndaDwagon)** for the upstream Wiki documentation
- **[Oskar](https://github.com/osrott61-gh)** for Odinpacks and Wiki contributions
- **[Mesazane](https://github.com/Mesazane)** for early build contributions

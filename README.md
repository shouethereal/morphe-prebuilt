# Morphe Pre-built
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)![Online](https://img.shields.io/discord/1434627744821547066?style=for-the-badge)](https://discord.gg/6WD7D9Xte6)
[![CI](https://img.shields.io/github/actions/workflow/status/shouethereal/morphe-prebuilt/ci.yml?branch=main&event=schedule&style=for-the-badge
)](https://github.com/shouethereal/morphe-prebuilt/actions/workflows/ci.yml)

Extensive ~~ReVanced~~ Morphe builder. Original repo https://github.com/j-hc/revanced-magisk-module

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li> Supports all present and future ReVanced apps (including projects implementing the same API)</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimizes APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
</details>

## If you are having trouble with the classic mount method of the modules
such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)

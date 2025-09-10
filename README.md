
# ReVanced Magisk Module (Fork)

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rvc_magisk)
[![CI](https://github.com/kkgarfin/revanced/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/kkgarfin/revanced/actions/workflows/ci.yml)

This is **my fork** of the original [ReVanced Magisk Module](https://github.com/j-hc/revanced-magisk-module) by [j-hc](https://github.com/j-hc).  
It mainly exists for my own use, experimentation, and tweaks — but feel free to use it if you find it helpful!  

👉 For the official and always up-to-date source, check the [main repository](https://github.com/j-hc/revanced-magisk-module).  

---

## 🔹 About this fork
- Based on the upstream repo, with occasional personal changes.
- May update CI or configs differently than the original.
- Still credits all main development work to [j-hc](https://github.com/j-hc).

---

## 📥 Downloads
- Get the [latest release from my fork](https://github.com/kkgarfin/revanced/releases).  
- Or see the [upstream releases](https://github.com/j-hc/revanced-magisk-module/releases) for the official builds.  

If you are using Magisk/KernelSU modules, you may also want [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from the Play Store.  

---

<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced and <a href="https://github.com/inotia00/revanced-patches">ReVanced Extended</a> apps</li>
 <li>Can build Magisk modules and non-root APKs</li>
 <li>Updated daily with the latest versions of apps and patches</li>
 <li>Optimize APKs and modules for size</li>
 <li>Modules</li>
   <ul>
     <li>recompile invalidated odex for faster usage</li>
     <li>receive updates from Magisk app</li>
     <li>do not break safetynet or trigger root detections</li>
     <li>handle installation of the correct version of the stock app and all that</li>
     <li>support Magisk and KernelSU</li>
   </ul>
</ul>
Note: the <a href="../../actions/workflows/ci.yml">CI workflow</a> builds modules and APKs daily via GitHub Actions if patches change. You may want to disable it.
</details>

---

## 🛠️ Customize Patches or Apps
 * Star this fork ⭐
 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Edit [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the [build workflow](../../actions/workflows/build.yml)
 * Get your modules and APKs from [releases](../../releases)

See also: [`CONFIG.md`](./CONFIG.md)

---

## 🏗️ Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
````

### On Desktop

```console
$ git clone https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```

---

### 🙌 Credits

All credit for the original work goes to [j-hc](https://github.com/j-hc).
This fork is just my personal variant — check the upstream repo for the source of truth.


---

<p align="center">
  <picture>
    <img src="assets/nobodyatall-banner.svg" alt="nobodyAtall — Android Kernel and Custom ROM Developer" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="https://xdaforums.com/m/nobodyatall.788040/"><img src="https://img.shields.io/badge/XDA-Developer-f59726?style=for-the-badge&logo=android&logoColor=white" alt="XDA Developers" /></a>
  <a href="https://github.com/nobodyAtall-code?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-233142?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories" /></a>
  <a href="https://github.com/nobodyAtall-code/copilot_project/blob/main/PROJECT_STATUS.md"><img src="https://img.shields.io/badge/Current%20work-Android%2016-2baf92?style=for-the-badge&logo=android&logoColor=white" alt="Current Android 16 project" /></a>
</p>

## Hello, I'm nobodyAtall (nAa) 👋

I'm an Android open-source enthusiast focused on **Linux kernels, custom Android ROMs, device bring-up, and the Android build system**.

My earlier work under the **nAa** name is associated with **MiniCM** (unofficial CyanogenMod ports) and custom kernels for classic Sony Ericsson Xperia devices — especially the **Xperia X8, X10 Mini, and X10 Mini Pro**. Today, I'm revisiting Android platform development with newer Xiaomi devices, kernel trees, vendor integration, and LineageOS bring-up.

> **From the early Xperia / CyanogenMod days to modern AOSP and Android 16.** This profile brings together the legacy source trees and the work in progress.

---

## 🚀 Current projects

| Project | What it does | Focus |
| --- | --- | --- |
| [Redmi Note 17 5G / mist — device tree](https://github.com/nobodyAtall-code/android_device_xiaomi_mist) | Android device configuration for a **LineageOS 23.2 / Android 16 bring-up**; still in development, **not a boot-confirmed release** | AOSP, device bring-up |
| [mist — vendor tree](https://github.com/nobodyAtall-code/proprietary_vendor_xiaomi_mist) | Curated device-specific proprietary vendor integration and build definitions | Vendor blobs, Soong |
| [mist — Linux kernel source](https://github.com/nobodyAtall-code/android_kernel_xiaomi_mist) | Device kernel source and build configuration for Xiaomi mist | Linux, Qualcomm |
| [mist — kernel integration](https://github.com/nobodyAtall-code/android_device_xiaomi_mist-kernel) | Stock-compatible kernel prebuilts / Android device integration | Boot images, ARM64 |
| [kernel_build](https://github.com/nobodyAtall-code/kernel_build) | Kernel build-related source and configuration | Kernel build tooling |
| [copilot_project](https://github.com/nobodyAtall-code/copilot_project) | Central research, GitHub Actions workflows, build investigations and engineering handover notes for mist | GitHub Actions, scripting, documentation |

**Live development notes:** [PROJECT_STATUS.md](https://github.com/nobodyAtall-code/copilot_project/blob/main/PROJECT_STATUS.md) — the source of truth for verified progress, open blockers, and next engineering steps. A successful research workflow does **not** mean the ROM has successfully booted.

---

## 🕹️ Legacy Android projects — the nAa era

These repositories preserve source and device work from the classic Android modding ecosystem. They are presented as **legacy/archival projects**, not current releases or supported downloads.

### nAa kernel families

| Repository | Purpose |
| --- | --- |
| [nAa-kernel](https://github.com/nobodyAtall-code/nAa-kernel) | Original nAa-branded custom Android kernel tree |
| [nAa-kernel-ics](https://github.com/nobodyAtall-code/nAa-kernel-ics) | Kernel development for the Android **Ice Cream Sandwich** generation |
| [nAa-kernel-jb](https://github.com/nobodyAtall-code/nAa-kernel-jb) | Kernel development for the **Jelly Bean** generation |
| [msm7x27-2.6.32.x-nAa](https://github.com/nobodyAtall-code/msm7x27-2.6.32.x-nAa) | Qualcomm MSM7x27 Linux 2.6.32 kernel source |
| [msm7x30-2.6.32.x-nAa](https://github.com/nobodyAtall-code/msm7x30-2.6.32.x-nAa) | Qualcomm MSM7x30 Linux 2.6.32 kernel source |
| [msm7x30-3.0.x-nAa](https://github.com/nobodyAtall-code/msm7x30-3.0.x-nAa) | Qualcomm MSM7x30 Linux 3.0 kernel source |
| [msm7x30-3.4.x-nAa](https://github.com/nobodyAtall-code/msm7x30-3.4.x-nAa) | Qualcomm MSM7x30 Linux 3.4 kernel source |
| [kernel_sony_fuji](https://github.com/nobodyAtall-code/kernel_sony_fuji) | Sony Fuji platform kernel source |

### Android device, vendor and hardware trees

| Repository | Purpose |
| --- | --- |
| [android_device_semc_mogami-common](https://github.com/nobodyAtall-code/android_device_semc_mogami-common) | Shared Sony Ericsson Mogami device configuration |
| [android_device_htc_passion](https://github.com/nobodyAtall-code/android_device_htc_passion) | HTC Passion / Nexus One Android device tree |
| [android_vendor_samsung_maguro](https://github.com/nobodyAtall-code/android_vendor_samsung_maguro) | Samsung Galaxy Nexus (maguro) vendor tree |
| [android_hardware_qcom_display](https://github.com/nobodyAtall-code/android_hardware_qcom_display) | Qualcomm display hardware integration |
| [XperiaFeatures](https://github.com/nobodyAtall-code/XperiaFeatures) | Xperia-related feature source |

### MiniCM & Xperia community history

**MiniCM7 / MiniCM9 / MiniCM10** were part of an era when the community brought newer versions of Android to small, resource-constrained Xperia phones. My historical nAa work focused on kernels and Android device enablement for that ecosystem.

- **Devices:** Sony Ericsson Xperia X8, Xperia X10 Mini and Xperia X10 Mini Pro.
- **Platform generations:** Gingerbread / CyanogenMod 7, Ice Cream Sandwich / CyanogenMod 9, and Jelly Bean-era work.
- **Key interests:** kernel customization, hardware compatibility, performance tuning, custom recovery, and helping older hardware run newer Android releases.

For historical discussion and release context, see the [XDA Developers profile](https://xdaforums.com/m/nobodyatall.788040/) and the community's [MiniCM archive](https://xperiaminicyanogen.wordpress.com/).

---

## 🧰 What I work with

| Area | Technologies |
| --- | --- |
| Kernel & low-level | Linux kernel, ARM / ARM64, Qualcomm platforms, kernel configuration |
| Android platform | AOSP, CyanogenMod, LineageOS, device / vendor trees, Android build system |
| Device bring-up | Boot and vendor images, proprietary integration, HAL/VINTF research, partition layout |
| Engineering workflow | Git, GitHub Actions, Linux shell, build automation, technical documentation |
| Debugging | ADB, Fastboot, boot logs, build troubleshooting, source-level investigation |

---

## 📊 GitHub activity

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=nobodyAtall-code&show_icons=true&hide_border=true&theme=github_dark" height="165" alt="GitHub contribution statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nobodyAtall-code&layout=compact&hide_border=true&theme=github_dark" height="165" alt="GitHub language statistics" />
</p>

<sub>Third-party GitHub statistics are generated dynamically and might not always load. Legacy repositories and imported source trees may affect language breakdowns.</sub>

---

## 🔗 Community & contact

- **XDA Developers:** [nobodyAtall](https://xdaforums.com/m/nobodyatall.788040/)
- **GitHub:** [@nobodyAtall-code](https://github.com/nobodyAtall-code)
- **Project progress:** [mist / LineageOS status](https://github.com/nobodyAtall-code/copilot_project/blob/main/PROJECT_STATUS.md)

<p align="center"><strong>Keep old devices useful. Keep Android open. Keep building.</strong></p>

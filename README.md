## 立子 · Lizi

**个人开发者 · Android 底层模块开发与异构系统移植**

> 正在把 **iOS 16.5（Darwin / XNU 22.5.0）** 移植到 **联发科天玑 8100（MT6895）** 平台。

[![酷安：六百斤的立子](https://img.shields.io/badge/%E9%85%B7%E5%AE%89-%E5%85%AD%E7%99%BE%E6%96%A4%E7%9A%84%E7%AB%8B%E5%AD%90-2C7BE5?style=flat-square&logo=android&logoColor=white)](https://www.coolapk.com/u/34747056)
[![Redmi Note 11T Pro](https://img.shields.io/badge/Redmi_Note_11T_Pro-xaga%20%C2%B7%20MT6895-orange?style=flat-square&logo=xiaomi&logoColor=white)](https://www.mi.com/)
[![OnePlus 13](https://img.shields.io/badge/OnePlus_13-PJZ110%20%C2%B7%20ColorOS%2016-black?style=flat-square&logo=oneplus&logoColor=white)](https://www.oneplus.com/cn/13)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![Windows](https://img.shields.io/badge/Windows-444C56?style=flat-square&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/windows)

### 代表项目

| 项目 | 核心架构与实现进展 |
| :--- | :--- |
| **[hakios-xaga](https://github.com/lizi600jin/hakios-xaga)**<br>`XNU 22.5.0` · `iOS 16.5` · `MT6895`<br>[![stars](https://img.shields.io/github/stars/lizi600jin/hakios-xaga?style=flat-square&color=6e7681)](https://github.com/lizi600jin/hakios-xaga) | **天玑 8100 平台 iOS 16.5 移植（实验性）**<br>打通 `LK → mtkloader → XNU` 引导链路，支持 UFS 挂载读取 APFS 文件系统，已点亮 `1080×2460 @ 60fps` 桌面用户态；触控、USB 与 GPU 驱动推进中。 |
| **[hifi-src-bypass](https://github.com/lizi600jin/hifi-src-bypass)**<br>`AudioFlinger` · `USB HAL` · `WebUI`<br>[![stars](https://img.shields.io/github/stars/lizi600jin/hifi-src-bypass?style=flat-square&color=6e7681)](https://github.com/lizi600jin/hifi-src-bypass) | **全机型 Android 音频重采样旁路直通**<br>逐层解除音频策略 XML、USB HAL 采样率表、厂商 HiFi 通道与音量曲线四处系统上限，打通 `96kHz → 384kHz`、`16 / 24 / 32-bit` 无损输出链路，附带 WebUI 与 `hifi doctor` 校验。 |
| **[oneplus13-audio-effect](https://github.com/lizi600jin/oneplus13-audio-effect)**<br>`OnePlus 13` · `Global EQ`<br>[![stars](https://img.shields.io/github/stars/lizi600jin/oneplus13-audio-effect?style=flat-square&color=6e7681)](https://github.com/lizi600jin/oneplus13-audio-effect) | **一加 13 内置扬声器全局均衡器**<br>针对内置扬声器定制全局频响调校，接入蓝牙或 USB 音频外设时自动旁路，避免外设音染。 |

### 技术栈与工具链

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=black) ![Java](https://img.shields.io/badge/Java-B07219?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

| 领域 | 涉及技术与组件 |
| :--- | :--- |
| **引导与内核移植** | `LK / XNU` · `APFS` · `设备树 (Device Tree)` · `adb / fastboot` |
| **Android 音频链路** | `AudioFlinger` · `ALSA / tinyalsa` · `USB Audio HAL` |
| **Root 生态与系统层** | `Magisk / KernelSU / APatch` · `systemless mount` · `SELinux` |

### 开源数据

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=lizi600jin&show_icons=true&count_private=true&include_all_commits=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&icon_color=58a6ff&text_color=8b949e&hide=issues,prs,contribs" alt="GitHub 统计" />
  &nbsp;
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=lizi600jin&layout=normal&langs_count=6&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e" alt="主要语言" />
</p>

## 立子 · Lizi

**个人开发者 · Android 系统层 · 内核移植 · 开发工具**

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
| **[dsh-ensp](https://github.com/lizi600jin/dsh-ensp)**<br>`eNSP` · `MCP` · `DSH Plugin`<br>[![stars](https://img.shields.io/github/stars/lizi600jin/dsh-ensp?style=flat-square&color=6e7681)](https://github.com/lizi600jin/dsh-ensp) | **华为 eNSP 实验自动化（npm `dsh-ensp`）**<br>生成 eNSP 可直接打开的 `.topo` 拓扑，自动启动设备并确认就绪，逐条下发配置、每条命令核对提示符返回后才继续；任一条出错即中断并回报行号、命令与设备原始输出。路由协议收敛走轮询断言而非固定等待。提供 CLI、MCP Server 与 DSH 插件三种调用方式，内置 23 个场景预设。 |

### 技术栈与工具链

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=black) ![Java](https://img.shields.io/badge/Java-B07219?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

| 领域 | 涉及技术与组件 |
| :--- | :--- |
| **引导与内核移植** | `LK / XNU` · `APFS` · `设备树 (Device Tree)` · `adb / fastboot` |
| **Android 音频链路** | `AudioFlinger` · `ALSA / tinyalsa` · `USB Audio HAL` |
| **Root 生态与系统层** | `Magisk / KernelSU / APatch` · `systemless mount` · `SELinux` |
| **开发工具与插件** | `Node.js` · `MCP` · `DeepSeek Harness` 插件 · eNSP 拓扑格式 |

### 开源数据

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=lizi600jin&show_icons=true&count_private=true&include_all_commits=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&icon_color=58a6ff&text_color=8b949e&hide=issues,prs,contribs" alt="GitHub 统计" />
  &nbsp;
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=lizi600jin&layout=normal&langs_count=6&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e" alt="主要语言" />
</p>

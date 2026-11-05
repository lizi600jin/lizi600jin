# 立子

· 一名个人开发者  
· 爱好安卓模块开发和系统移植  
· 正在把 iOS 跑上联发科天玑 8100

---

**我的酷安**

[![酷安：六百斤的立子](https://img.shields.io/badge/%E9%85%B7%E5%AE%89-%E5%85%AD%E7%99%BE%E6%96%A4%E7%9A%84%E7%AB%8B%E5%AD%90-2C7BE5?style=flat-square&logo=android&logoColor=white)](https://www.coolapk.com/u/34747056)

**在役设备**

[![Redmi Note 11T Pro](https://img.shields.io/badge/Redmi_Note_11T_Pro-xaga%20%C2%B7%20MT6895-orange?style=flat-square&logo=xiaomi&logoColor=white)](https://www.mi.com/)
[![OnePlus 13](https://img.shields.io/badge/OnePlus_13-PJZ110%20%C2%B7%20ColorOS%2016-black?style=flat-square&logo=oneplus&logoColor=white)](https://www.oneplus.com/cn/13)

**开发系统**

[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![Windows](https://img.shields.io/badge/Windows-444C56?style=flat-square&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/windows)

**技术栈**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=black) ![Java](https://img.shields.io/badge/Java-B07219?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

AudioFlinger · ALSA / tinyalsa · Magisk / KernelSU / APatch · systemless `mount --bind` · SELinux · LK / XNU · APFS · 设备树 · adb / fastboot · Git

**代表项目**

- [**hifi-src-bypass**](https://github.com/lizi600jin/hifi-src-bypass) [![stars](https://img.shields.io/github/stars/lizi600jin/hifi-src-bypass?style=flat-square&color=6e7681)](https://github.com/lizi600jin/hifi-src-bypass) — 全机型 Android 音频直通。逐层解除音频策略 XML、USB HAL 采样率表、厂商 HiFi 通道、音量曲线四处上限，消除系统级重采样；96k → 384k，16 / 24 / 32 bit，配 WebUI 与 `hifi doctor` 深度校验。
- [**hakios-xaga**](https://github.com/lizi600jin/hakios-xaga) [![stars](https://img.shields.io/github/stars/lizi600jin/hakios-xaga?style=flat-square&color=6e7681)](https://github.com/lizi600jin/hakios-xaga) — XNU（Darwin Kernel 22.5.0）与 iOS 16.5 用户态跑在天玑 8100 上，已点亮桌面：引导链 LK → mtkloader → XNU，UFS 读取 APFS，1080×2460 / 60 fps。实验性项目，触控、USB、GPU 尚未完成。
- [**oneplus13-audio-effect**](https://github.com/lizi600jin/oneplus13-audio-effect) [![stars](https://img.shields.io/github/stars/lizi600jin/oneplus13-audio-effect?style=flat-square&color=6e7681)](https://github.com/lizi600jin/oneplus13-audio-effect) — 一加 13 内置扬声器全局 EQ，插蓝牙 / USB 自动旁路。

**开源数据**

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=lizi600jin&show_icons=true&count_private=true&include_all_commits=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&icon_color=58a6ff&text_color=8b949e&hide=issues,prs,contribs" alt="GitHub 统计" />
</p>

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=lizi600jin&layout=normal&langs_count=6&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e" alt="主要语言" />
</p>

<!--
维护说明（主页不显示）：

1. 发布方式
   建同名仓库 lizi600jin（GitHub login 不支持中文，账号名保持 lizi600jin；显示名 Name 已设为「立子」），
   本文件放仓库根目录即渲染为个人主页。需一并上传：README.md、assets/github-stats.svg、
   assets/github-langs.svg、.github/workflows/refresh-cards.yml。assets/banner.png 已弃用，不必上传。

2. 正文结构（按你的要求定稿）
   三行式简介（照天天的写法）→ 我的酷安 → 在役设备 → 开发系统 → 技术栈 → 代表项目（3 条）→ 开源数据。
   已删除：「简介要点」「联系」两节、设备下方的说明性小注释、历史停更仓库 op13-hifi-src-bypass。
   全文无 emoji、无求 star 语句、无图片横幅。

3. 统计卡（开源数据）实测结论
   - 现用 github-readme-stats-eight-theta.vercel.app，每次请求实时读取 GitHub API。
     数值已核对真实：Stars 24（与 API 合计一致）、Commits 174；语言占比
     Shell 45.01% / C 32.41% / JavaScript 8.87% / Awk 6.36% / HTML 4.11% / Go Template 3.24%。
     连测 5 次全部正常返回。
   - 其它服务本轮不可用，故未写入正文：官方公共实例 503 限流；σ5 等镜像返回
     "Maximum retries exceeded"（该实例未配 PAT）；trophy / activity-graph 返回 402；
     streak-stats.demolab.com 已不可达。空白卡比没有卡更减分，所以宁可不放。
   - 国内访客可达性：GitHub 渲染 README 时会把外链图片改写成 camo.githubusercontent.com
     （解析到 185.199.x，GitHub 自己的 CDN，本机直连实测 200 可取到 SVG）。即由 GitHub 服务器
     去抓 vercel 的图，访客不需要直连 vercel.app——本机 vercel 不通不代表访客看不到。
     但 camo 有缓存且偶发 502（实测 anuraghazra 的一张 stats 卡就是 502），因此保留兜底方案：
     把上面两处 src 改成相对路径 assets/github-stats.svg 与 assets/github-langs.svg，
     配合 refresh-cards.yml 每小时自动重抓并提交（fetch 逻辑已本机试跑通过）。
     该方案图片走 GitHub CDN 必定能加载，代价是"每小时更新"而非"每次访问实时"。
     要最稳的实时效果，就自己 fork 部署一份 github-readme-stats（Vercel 免费，配 PAT_1 环境变量），
     把域名换成自己的实例——天天用的正是他自建的 miyuki-github.vercel.app。

4. stats 卡加了 hide=issues,prs,contribs：这三项当前均为 0，显示出来只有减分作用；
   有真实数据后从 URL 与 workflow 里删掉该参数即可恢复。

5. 徽章均为可点击链接：酷安 → uid 34747056 主页；设备 → 厂商产品页；系统 → 官网；stars → 贡献者列表。

6. 待补信息（见 SETUP.md §7.2）：教育背景 / 目标岗位 / 投递邮箱。
-->

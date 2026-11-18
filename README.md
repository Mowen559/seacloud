# SeaCloud (海阔视界客户端 / 低代码平台测试器) 🌊

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](./LICENSE)
[![Disclaimer: Official](https://img.shields.io/badge/Disclaimer-Official-red.svg)](./DISCLAIMER.md)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Windows-green.svg)]()
[![Status: Beta](https://img.shields.io/badge/Status-Beta%20Tester-blueviolet.svg)]()
[![Author](https://img.shields.io/badge/Author-Mowen559-orange.svg)](https://github.com/Mowen559)

> **SeaCloud** 是一款基于 Flutter 构建的高性能、现代化的**测试版低代码平台测试器（多端动态规则与 UI 组件执行沙箱）**，原生支持 Android 移动端与 Windows PC 桌面端。深度集成海阔视界低代码规则生态、低代码动态组件渲染系统（如 21:9 轮播大屏、瀑布流、双列影视卡片、选集矩阵等）、工业级 MPV 音视频引擎、QuickJS 同构脚本沙箱与 60fps 轨道式弹幕渲染系统，专为低代码规则开发调试、动态组件可视化求值与流媒体链路实测而设计。

> [!IMPORTANT]
> ⚖️ **发版免责声明**：本软件为开源中立的通用媒体播放与规则执行沙箱，官方发行包中**坚决不内置、不提供、不分发任何受版权保护的音视频或图文内容**。使用前请务必仔细阅读完整版 [《官方发版免责声明》(DISCLAIMER.md)](./DISCLAIMER.md)。

---

## ⚖️ 严正开源协议与版权使用声明 (Mandatory Attribution & Copyleft Policy)

本项目采用 **[GNU General Public License v3.0 (GPL-3.0)](./LICENSE)** 强互惠（Strong Copyleft）开源许可证。

为保障原作者核心权益，杜绝任何未经授权的闭源霸占或隐匿署名行为，任何个人、开源团体、组织或商业实体在获取、使用、引用、分发、二次开发或基于本项目代码衍生作品时，**必须无条件严格遵守以下法律与授权条款**：

### 1. 强制保留原作者署名与版权归属 (Mandatory Attribution)
- 任何基于本项目源码（无论是否经过修改、重构或片段引用）构建的软件产品或衍生作品，**必须在最终交付物的所有显著位置（包括但不限于：软件启动页/关于对话框、官方文档首页、软件发布主页、README 头部及所有涉及的源文件文件头）显著声明其使用了 Mowen559 的代码**；
- 显式声明文案规范：
  ```text
  Portions of this software are derived from SeaCloud / DeepCloud Client
  Copyright (C) 2026 Mowen559 (https://github.com/Mowen559/seacloud)
  Licensed under the GNU General Public License v3.0 (GPL-3.0).
  ```

### 2. 强传染互惠开源铁律 (Strict Copyleft)
- 本协议具有不可撤销的强传染性。任何包含、链接或衍生自本项目代码的软件，**其全部源代码亦必须在向公众分发或交付的同时，以相同的 GPL-3.0 协议完全对外公开开源**；
- **绝对禁止将本项目代码或其派生版本包装为闭源商业软件销售或发布**。

### 3. 禁止移除或篡改版权元数据
- 严禁删除、隐匿或修改代码仓库与最终安装包中的 `LICENSE` 文件、作者署名、Commit 历史或版权元数据。

> [!CAUTION]
> 任何违反上述条款（包括但不限于隐瞒作者出处、抹除原作者署名、闭源商用等行为）将构成对 GNU GPL-3.0 协议的直接侵害，原作者依法保留追究侵权责任及申请开源合规维权之一切权利。

---

## 🚀 核心特性

- 📱 **多端统一响应式架构**：基于 Flutter 3 构建，原生支持 Android 移动端（自适应竖屏/折叠屏）、Windows 桌面端，同一套业务模型，像素级质感呈现。
- 🎬 **专业级多媒体播放器**：
  - 集成工业级硬件加速解码播放，最高画质置顶与 Master 物理码率自动感知；
  - 智能自适应防溢出界面：小屏模式下提供沉浸式底部参数调节抽屉（倍速、画质、比例切换）；
  - 操作栏智能活跃保活：默认 8 秒宽裕驻留，触控交互实时自动续期。
- 💬 **弹幕双擎保障**：Weeblify 免鉴权镜像优先 + 官方签名通道热备，60fps 轨道式高帧率渲染。
- 📡 **DLNA 大屏投屏与 DMR 接收**：支持跨设备大屏投屏互动。
- 🧩 **全功能 Hiker JS 规则沙箱**：内置动态微内核沙箱与同步网络桥接，完美驱动海阔视界全网影视、音乐与信息流规则生态。

---

## 📦 Releases 安装包下载 (GitHub Releases)

最新测试版安装包已发布至 **[GitHub Releases: v1.0.1 测试版](https://github.com/Mowen559/seacloud/releases/tag/v1.0.1)**，欢迎下载体验并反馈测试建议：

| 平台 | 最新资产文件名 | GitHub Releases 直达 | 仓库内置归档 | 说明 |
| :--- | :--- | :--- | :--- | :--- |
| **Android 移动端** | `seacloud-android-v1.0.1.apk` | [GitHub 下载 (v1.0.1)](https://github.com/Mowen559/seacloud/releases/download/v1.0.1/seacloud-android-v1.0.1.apk) | [dist 目录下载](./dist/seacloud-android-v1.0.0.apk) | 适用于 Android 7.0+ 手机/平板/车机，集成最新 HTTP/1.1 协议自愈与纯算力 PoW 引擎 |
| **Windows 桌面端** | `seacloud-windows-x64-v1.0.1.zip` | [GitHub 下载 (v1.0.1)](https://github.com/Mowen559/seacloud/releases/download/v1.0.1/seacloud-windows-x64-v1.0.1.zip) | [dist 目录下载](./dist/seacloud-windows-x64-v1.0.0.zip) | 适用于 Win 10/11 64位，解压即用绿色免安装版本（含完整 MPV 及 QuickJS 依赖库） |

> 完整发版日志请参阅 [Release Notes v1.0.1](./release-notes-v1.0.1.md) 与 [校验和清单](./dist/SHA256SUMS.txt)。

---

## ⚖️ 官方发版免责声明 (Release Disclaimer)

在下载、安装或使用本项目发布的任何安装包之前，请务必仔细阅读完整版 [《官方发版免责声明》(DISCLAIMER.md)](./DISCLAIMER.md)：
1. **纯中立执行环境**：官方发行版坚决不内置、不转码、不托管、不分发任何第三方受版权保护的音视频或图文内容；
2. **规则与数据源自治**：用户自行导入或加载的第三方规则与网络媒体流，其版权与法律责任完全由使用者自行独立承担，开发者概不承担连带责任；
3. **本地隐私安全**：播放记录与自定义规则 100% 留存在用户本地设备，零云端搜集；
4. **侵权即时下架 (Notice-and-Takedown)**：严格恪守避风港原则，若涉嫌侵权请提交 [GitHub Issue](https://github.com/Mowen559/seacloud/issues)，我们将在 24 小时内核实并下架相关资产。

---

## 👨‍💻 作者与支持

- 作者：**Mowen559**
- 官方仓库：[https://github.com/Mowen559/seacloud](https://github.com/Mowen559/seacloud)
- 源码协议：[GNU General Public License v3.0](./LICENSE)

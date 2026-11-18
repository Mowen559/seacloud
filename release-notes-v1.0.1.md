# SeaCloud v1.0.1 测试版 (低代码平台测试器) 🌊

> **版本定位**：本版本为 **测试版的低代码平台测试器 (Low-Code Platform Test Runner - Beta)**。
> 作为中立、轻量、高性能的多端执行沙箱与规则渲染容器，专为验证与调试海阔视界低代码规则生态、低代码动态页面组件渲染（如 21:9 沉浸式大屏轮播、瀑布流、双列影视卡片、自适应胶囊控件等）、QuickJS 脚本引擎与跨端多媒体播放器链路而构建。

---

## ⚖️ 严正开源协议与版权使用声明 (Mandatory Attribution & Copyleft Policy)

本项目采用 **[GNU General Public License v3.0 (GPL-3.0)](https://github.com/Mowen559/seacloud/blob/main/LICENSE)** 强互惠开源许可证。

为保障原作者核心权益，杜绝任何未经授权的闭源霸占或隐匿署名行为，任何个人、开源团体、组织或商业实体在获取、使用、引用、分发、二次开发或基于本项目代码衍生作品时，**必须无条件严格遵守以下法律与授权条款**：

1. **强制保留原作者署名与版权归属 (Mandatory Attribution)**：
   任何基于本项目源码（无论是否经过修改、重构或片段引用）构建的软件产品或衍生作品，**必须在最终交付物的所有显著位置显著声明其使用了 Mowen559 的代码**；
   - 显式声明文案规范：
     ```text
     Portions of this software are derived from SeaCloud / DeepCloud Client
     Copyright (C) 2026 Mowen559 (https://github.com/Mowen559/seacloud)
     Licensed under the GNU General Public License v3.0 (GPL-3.0).
     ```
2. **强传染互惠开源铁律 (Strict Copyleft)**：
   本协议具有不可撤销的强传染性。任何包含、链接或衍生自本项目代码的软件，其全部源代码亦必须在向公众分发的同时，以相同的 GPL-3.0 协议完全对外公开开源；绝对禁止包装为闭源商业软件销售或发布。
3. **禁止移除或篡改版权元数据**：
   严禁删除、隐匿或修改代码仓库与最终安装包中的 LICENSE 文件、作者署名、Commit 历史或版权元数据。

---

## 🛠️ 测试版核心改进与低代码测试特性

1. **低代码可视化组件渲染与极速求值**：
   - 完整驱动 `banner_carousel`（21:9 沉浸式大屏轮播）、`movie_3`（影视海报卡片）、`movie_2`（瀑布流双列卡片）、`flex_button`（自适应胶囊按钮）及多级选集控件（`text_2` / `text_3` / `text_4`）；
   - 内置 QuickJS 规则沙箱与动态 DOM 映射极速求值，毫秒级响应。
2. **双端网络协议握手自愈与算力引擎升级**：
   - 全面引入 HTTP/1.1 协议握手自愈机制，解决特定高防与移动网络环境下的握手挂起问题；
   - 纯算力 PoW 求解器与加解密引擎全面加固，页面加载零阻塞；
   - 完善 SQLite 数据库状态机与连接保护，防止并发写入死锁。
3. **专业级 MPV 原生内核与轨道式弹幕调度**：
   - Windows 桌面端与 Android 移动端全面对齐 MPV 高清硬件解码；
   - 60fps 轨道式高帧率弹幕渲染，支持 Weeblify 免鉴权镜像优先与官方签名通道热备。

---

## 📦 下载与文件完整性校验 (Checksums)

| 资产文件 | 平台 | 大小 | 说明 | SHA-256 校验和 |
| :--- | :--- | :--- | :--- | :--- |
| `seacloud-android-v1.0.1.apk` | Android 7.0+ (ARM64/x86_64) | 52.8 MB | 移动端低代码测试器 | `ca261c2782922eddd460c634a1ee52d400b65c67ee3c719d508120c259636526` |
| `seacloud-windows-x64-v1.0.1.zip` | Windows 10/11 64位 | 34.1 MB | PC桌面端低代码测试器 (绿色免安装) | `93a9511a438ae199334442517382b484f8519bf65e9188f04b26fd7d82ff0b3b` |

---
**原作者**：[Mowen559](https://github.com/Mowen559)  
**官方源码仓库**：[https://github.com/Mowen559/seacloud](https://github.com/Mowen559/seacloud)

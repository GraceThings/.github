<div align="center">

# 🌱 GraceThings

**Crafting thoughtful, native, and privacy-respecting Android tools.**  
*打造优雅、原生、注重隐私与体验的 Android 应用与生产力工具*

<br/>

[![Kotlin](https://img.shields.io/badge/Kotlin-2.0+-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Platform-Android_11+-3DDC84?style=flat-square&logo=android&logoColor=white)](https://www.android.com/)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Material 3](https://img.shields.io/badge/Design-Material_You_(M3)-blueviolet?style=flat-square&logo=materialdesign&logoColor=white)](https://m3.material.io/)
[![Local First](https://img.shields.io/badge/Architecture-Local--First-success?style=flat-square&logo=sqlite&logoColor=white)](#-our-philosophy)
[![Open Source](https://img.shields.io/badge/Open_Source-❤️-red?style=flat-square)](#)

<br/>
**[English](README.md)** | **[中文说明](README-CN.md)**

</div>

---

## 🌿 About Us / 关于 GraceThings

**GraceThings** 专注于构建原生、轻量、纯粹且尊重隐私的 Android 应用程序。我们坚信好的工具应当：
- **不打扰用户**：没有无休止的广告和后台驻留流氓行为，没有侵入式的隐私收集。
- **尊重系统生态**：紧跟最新 Android 设计语言（Jetpack Compose & Material You），在无需 Root 的前提下挖掘系统的原生潜能。
- **掌控数据主权**：坚守 **Local-First** 原则，所有核心数据本地存储，提供透明的备份与导出。

---

## 🚀 Featured Projects / 精选项目

<div align="center">

| 项目 | 类型 | 核心亮点 | 获取与体验 |
| :--- | :--- | :--- | :--- |
| **[Bubble Notice](#-bubble-notice)** | 智能气泡通知控制台 | 系统级悬浮气泡、通知智能堆叠、免 Root/Shizuku、沉浸勿扰 | [![Google Play](https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=io.github.gracethings.bubblenotice) [![F-Droid](https://img.shields.io/badge/F--Droid-1976D2?style=flat-square&logo=f-droid&logoColor=white)](https://f-droid.org/en/packages/io.github.gracethings.bubblenotice/) [![GitHub](https://img.shields.io/badge/GitHub-Releases-black?style=flat-square&logo=github)](https://github.com/GraceThings/bubble-notice-android/releases) |
| **[Pixel World](#-pixel-world)** | 真实世界迷雾足迹记录器 | 双精度追踪引擎、智能活动休眠省电、真实行政区界与球面积分算法、离线成就 | [![Releases](https://img.shields.io/badge/GitHub-Releases-black?style=flat-square&logo=github)](https://github.com/GraceThings/pixel-world-releases/releases) [![Issues](https://img.shields.io/badge/Report-Issues-orange?style=flat-square&logo=github)](https://github.com/GraceThings/pixel-world-releases/issues) |
| **[SuiDays](#-suidays)** | 现代极简农历/公历倒数日 | Material 3 动态色彩、公历/农历完整支持、系统日历双向同步、精美分享卡片 | [![MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](https://github.com/GraceThings/suidays) [![GitHub](https://img.shields.io/badge/Repo-SuiDays-black?style=flat-square&logo=github)](https://github.com/GraceThings/suidays) |

</div>

<br/>

### 💬 [Bubble Notice](https://github.com/GraceThings/bubble-notice-android)
> **Android 系统级智能气泡通知与控制台 / Smart Floating Bubble Notifications**

为 Android 11+（包括 Android 15/16/17 多任务气泡）量身定制的轻量级悬浮通知增强工具，**无需 Root 或 Shizuku** 即可实现直观的全局悬浮气泡与统一通知管理。

* 🔔 **系统级悬浮气泡**：自由订阅高频应用通知，重要消息以悬浮气泡常驻，随时呼出与交互。
* 📦 **智能合并与扩展**：同类通知智能折叠堆叠，轻触即平滑展开完整内容与快捷原生操作（如“已读”、“回复”）。
* ⚡ **直达会话与跳转**：点击控制台未读卡片或悬浮气泡，一键直达对应应用与特定聊天页面。
* 🎛️ **统一通知控制台**：在一个集中化仪表盘中统一阅览与批处理所有未读消息。
* 🛡️ **专注与全屏友好**：全屏看剧/游戏时自动隐身，边缘滑动即呼出，支持随时滑动划走，告别打扰。

🔗 **快速链接**：
[GitHub 仓库](https://github.com/GraceThings/bubble-notice-android) · [Google Play](https://play.google.com/store/apps/details?id=io.github.gracethings.bubblenotice) · [F-Droid](https://f-droid.org/en/packages/io.github.gracethings.bubblenotice/) · [最新发布 Release](https://github.com/GraceThings/bubble-notice-android/releases)

---

### 🌍 [Pixel World](https://github.com/GraceThings/pixel-world-releases)
> **现实世界迷雾探索与足迹记录器 / Fog of World Footprint Chronicler**

将地球划分为数百万个微观网格，在后台静默记录真实生活足迹，驱散地图未知的“迷雾”。无论是日常通勤还是环球旅居，Pixel World 都是你忠实的数字足迹编年史。

* 🗺️ **双精度记录引擎 (Dual-Precision Engine)**：
  * **高精模式 (Zoom 18)**：精细至街道与胡同，专为步行漫游、徒步登山打造。
  * **省电模式 (Zoom 14)**：区县级低功耗网格，适合日常通勤、驾车自驾与高铁巡游。
* 🔋 **智能活动休眠感知**：集成 Activity Recognition，静止时自动挂起 GPS 定位进入深度休眠，检测到移动瞬间无感唤醒。
* 🏙️ **真实地理界线与球面精算**：通过 OpenStreetMap Nominatim 自动获取真实省市/行政边界，告别粗糙矩形包围盒，基于球面多边形线积分精准计算探索面积与占比。
* 🏆 **丰富离线成就体系**：支持从青铜至黑曜石阶梯成就（如 *Earth Walker*、*Globetrotter*、*Pathfinder Fever*），每日 21:00 定时推送探索日报。
* 🗄️ **100% 数据主权**：所有瓦片网格与轨迹纯本地存储（Room Database），支持一键 JSON 完整冷备份与恢复。

🔗 **快速链接**：
[Releases 仓库](https://github.com/GraceThings/pixel-world-releases) · [Google Play](https://play.google.com/store/apps/details?id=com.velviagris.adventure) · [反馈与建议 Issues](https://github.com/GraceThings/pixel-world-releases/issues)

---

### 🗓️ [SuiDays](https://github.com/GraceThings/suidays)
> **现代极简公历/农历倒数日与纪念日管理 / Modern Solar & Lunar Countdown**

基于 Jetpack Compose 与 Material 3 设计语言构建的倒数日与时光记录工具，专注纯粹记录与视觉美感，离线无广告。

* 🎨 **Material You 动态色彩**：原生 Android 设计风格，完美适配深色模式与壁纸动态取色主题。
* 🌙 **公历与农历双轨支持**：完整支持农历生日、传统节气与节日计算（基于 `lunar-java`）。
* 🔄 **灵活重复与高级提醒**：支持天/周/月/年自定义重复，多级提前通知与系统闹钟提醒联动。
* 📅 **系统日历自动同步**：一键将倒数日程双向写入 Android 系统日历，生态联动无缝隙。
* 🖼️ **精美仪式感分享卡片**：一键渲染高分辨率倒数日视觉海报，分享给好友或保存相册。
* 🔒 **隐私至上与本地化**：零广告、零统计 SDK、零网络追踪，数据支持一键导出/合并本地 JSON。

🔗 **快速链接**：
[GitHub 仓库](https://github.com/GraceThings/suidays) · [Google Play](https://play.google.com/store/apps/details?id=io.github.gracethings.suidays) · [开源许可证 MIT](https://github.com/GraceThings/suidays/blob/master/LICENSE)

---

## 💡 Our Philosophy / 核心理念

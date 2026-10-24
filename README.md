<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>硬件与物联网精选</h1>
<p>从固件到平台、从开发板到界面：能直接上手折腾的嵌入式与物联网项目</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-iot?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-iot?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-iot?style=flat-square&color=8250df"></p>

<p><a href="README.en.md">English</a> · <a href="CONTRIBUTING.md">参与贡献</a> · <a href="REFERENCES.md">借鉴的清单</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">全部合集</a></p>
</div>

> **28 个项目，共 555k Stars。** Stars、许可证、最近提交时间由 GitHub API 实时读取，数据更新于 2026-10-24。排名按 Stars 排序，仅作热度参考，不代表质量。

<sub>读表说明：Stars 与「更新」都是生成时从 GitHub API 读到的真实值；许可证取自仓库；括号里是使用前要知道的限制。</sub>

## 30 秒选型

| 你的情况 | 从这里开始 |
|:--|:--|
| 让家里设备自己联动 | [Home Assistant](https://github.com/home-assistant/core) — 本地优先、设备接入最多，自动化可以完全离线跑 |
| 一块 ESP32 做联网设备 | [ESPHome](https://github.com/esphome/esphome) — 写 YAML 就能刷固件，和 Home Assistant 原生打通 |
| 设备要接几万台 | [EMQX](https://github.com/emqx/emqx) — MQTT 集群成熟，规则引擎能把数据直接转出去 |
| 设备上带一块屏 | [LVGL](https://github.com/lvgl/lvgl) — 低资源也能跑流畅界面，MCU 上的事实标准 |

## 目录

- [家居与设备平台](#家居与设备平台)
- [固件与开发板](#固件与开发板)
- [设备界面与工具链](#设备界面与工具链)
- [数据与固件分析](#数据与固件分析)
- [学习与入门](#学习与入门)

## 家居与设备平台

_先选平台，再选设备，顺序反了会重复造轮子。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [Home Assistant](https://github.com/home-assistant/core) | 本地优先的智能家居中枢，设备接入极多，自动化可视化编辑 | 91.7k | `Apache-2.0` | 2026-10 |
| [Node-RED](https://github.com/node-red/node-red) | 拖节点连线做设备联动，不写代码也能接 MQTT/HTTP | 23.8k | `Apache-2.0` | 2026-10 |
| [ThingsBoard](https://github.com/thingsboard/thingsboard) | 设备管理、数据采集、规则引擎一体的 IoT 平台 | 22.6k | `自定义` | 2026-10 |
| [EMQX](https://github.com/emqx/emqx) | 高并发 MQTT broker，百万连接级别，支持规则转发 | 16.9k | `自定义` | 2026-10 |
| [ESPHome](https://github.com/esphome/esphome) | 用 YAML 生成 ESP 固件，和 Home Assistant 原生打通 | 11.9k | `自定义` | 2026-10 |
| [Mosquitto](https://github.com/eclipse-mosquitto/mosquitto) | 轻量 MQTT broker，树莓派就能跑，协议实现最标准 | 11.3k | `自定义` | 2026-10 |
| [xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server) | 给 xiaozhi-esp32 做后端，快速搭语音设备服务端 | 11.0k | `MIT` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 固件与开发板

_刷机前先确认设备型号与回滚方式。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) | 基于 MCP 的语音聊天机器人，ESP32 上跑中文对话 | 31.8k | `MIT` | 2026-10 |
| [Tasmota](https://github.com/arendst/Tasmota) | 免写代码给插座灯泡刷固件，本地控制不依赖云 | 24.9k | `GPL-3.0` | 2026-10 |
| [MicroPython](https://github.com/micropython/micropython) | 单片机上跑 Python，改一行看一行，调试最快 | 22.1k | `自定义` | 2026-10 |
| [QMK Firmware](https://github.com/qmk/qmk_firmware) | 键盘固件，自定义键位、分层与宏 | 20.8k | `GPL-2.0` | 2026-10 |
| [WLED](https://github.com/wled/WLED) | 灯带效果控制器，网页调色与音乐同步 | 18.9k | `EUPL-1.2` | 2026-10 |
| [Marlin](https://github.com/MarlinFirmware/Marlin) | RepRap 3D 打印机固件，8 位与 32 位都支持 | 17.6k | `GPL-3.0` | 2026-10 |
| [Arduino ESP32](https://github.com/espressif/arduino-esp32) | ESP32 官方 Arduino 核心，入门首选 | 17.6k | `LGPL-2.1` | 2026-10 |
| [Zephyr](https://github.com/zephyrproject-rtos/zephyr) | 工业级 RTOS，多架构支持，认证与长期维护 | 16.9k | `Apache-2.0` | 2026-10 |
| [RT-Thread](https://github.com/RT-Thread/rt-thread) | 国产 RTOS，组件丰富，中文资料多 | 12.3k | `Apache-2.0` | 2026-10 |
| [Klipper](https://github.com/Klipper3d/klipper) | 3D 打印机固件，把计算放到上位机，精度更高 | 12.0k | `GPL-3.0` | 2026-10 |
| [Betaflight](https://github.com/betaflight/betaflight) | 穿越机飞控固件，调参与社区生态成熟 | 11.7k | `GPL-3.0` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 设备界面与工具链

_决定开发速度的一层，别等硬件定型才补。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [LVGL](https://github.com/lvgl/lvgl) | 嵌入式 GUI 库，低资源设备也能做出流畅界面 | 25.0k | `MIT` | 2026-10 |
| [TinyGo](https://github.com/tinygo-org/tinygo) | 用 Go 写单片机程序，二进制小、并发模型好 | 17.8k | `自定义` | 2026-10 |
| [Johnny-Five](https://github.com/rwaldron/johnny-five) | 用 JavaScript 控制 Arduino 与传感器，适合快速验证（长期未更新（2023-10），仅作参考） | 13.4k | `自定义` | 2023-10 |
| [Mongoose](https://github.com/cesanta/mongoose) | 单文件嵌入式 Web 服务器，带 TCP/IP、MQTT、WebSocket | 13.1k | `自定义` | 2026-10 |
| [Embassy](https://github.com/embassy-rs/embassy) | Rust 异步嵌入式框架，省电且类型安全 | 10.0k | `Apache-2.0` | 2026-10 |
| [PlatformIO](https://github.com/platformio/platformio-core) | 跨平台嵌入式构建工具，依赖与烧录一条命令 | 9.6k | `Apache-2.0` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 数据与固件分析

_设备一多，瓶颈就从代码变成数据。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [TDengine](https://github.com/taosdata/TDengine) | 时序数据库，专为设备数据的高写入量优化 | 25.2k | `AGPL-3.0` | 2026-10 |
| [Binwalk](https://github.com/ReFirmLabs/binwalk) | 固件拆包与特征分析，逆向和审计的第一步 | 14.5k | `MIT` | 2026-08 |

<sub>[回到目录](#目录)</sub>

## 学习与入门

_先搭硬件再谈项目，课程能省掉大量试错。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [IoT for Beginners](https://github.com/microsoft/IoT-For-Beginners) | 微软 12 周课程，从传感器到云端项目齐备 | 17.2k | `MIT` | 2026-05 |
| [Embedded Roadmap](https://github.com/m3y54m/Embedded-Engineering-Roadmap) | 嵌入式工程师学习路线图，标出每阶段该学什么 | 13.7k | `CC-BY-SA-4.0` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 为什么值得看

物联网清单最容易混进“只有原理图、没有固件”的项目。这里只保留能烧录、有文档、有社区的项目，并把**自己焊板子的**和**只想让家里设备听话的**分开，避免一上来就被 RTOS 吓退。

## 收录标准

- 有明确用途，README 能看懂、能跑起来；不收录只发概念或演示视频的项目。
- 许可证明确，仓库未归档；长期不更新的项目会标注并移出主表。
- 同一定位只留一个首选，同类项目放进同一小节横向对比，不做堆砌。
- Stars 只作参考，主要看维护频率、issue 响应和文档质量。
- 每条说明写清“解决什么问题、适合谁”，不搬运项目自述。

## 参与贡献

发现更好的项目、链接失效或说明有误？欢迎开 issue 或直接提交 PR，格式与要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。收录后会在下一次生成时自动带上真实 Stars 与许可证。

## 关于这份清单

- 表里的 Stars、许可证、最近提交都是生成时从 GitHub API 拉取的，不是手写数字，所以不会过期。
- 每次增删项目只改一份精选数据，再跑生成脚本，中英文两个版本与 Stars 同时更新。
- 如果这份清单帮你少翻了十几个仓库，点个 **Star** 是最直接的支持：[⭐ Star awesome-iot](https://github.com/AwesomeRepoHub/awesome-iot/stargazers)

## 许可

内容采用 [MIT](LICENSE) 许可，可自由转载，注明来源即可。项目本身的版权与许可归各作者所有。

---

<sub>本文件由脚本从精选数据与 GitHub API 自动生成，请勿直接编辑；增删条目见 [CONTRIBUTING.md](CONTRIBUTING.md)。</sub>

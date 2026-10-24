<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>Awesome IoT</h1>
<p>Firmware to platform, dev boards to device UIs — embedded and IoT projects you can actually flash today</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-iot?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-iot?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-iot?style=flat-square&color=8250df"></p>

<p><a href="README.md">中文</a> · <a href="CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">All collections</a></p>
</div>

> **17 projects, 412k stars in total.** Stars, licenses and last-commit dates are pulled from the GitHub API and refreshed on 2026-10-24. Sorted by stars for reference only — popularity is not quality.

## Pick in 30 seconds

| Your situation | Start here |
|:--|:--|
| Automate the house | [Home Assistant](https://github.com/home-assistant/core) — local-first, widest device support, automations run offline |
| A WiFi device on ESP32 | [ESPHome](https://github.com/esphome/esphome) — YAML to firmware, with first-class Home Assistant integration |
| Tens of thousands of devices | [EMQX](https://github.com/emqx/emqx) — battle-tested MQTT clustering with a rule engine |
| A device with a screen | [LVGL](https://github.com/lvgl/lvgl) — smooth UI on tiny MCUs; the de-facto embedded GUI library |

## Contents

- [Home automation and platforms](#home-automation-and-platforms)
- [Firmware and boards](#firmware-and-boards)
- [Device UI and toolchain](#device-ui-and-toolchain)
- [Data and firmware analysis](#data-and-firmware-analysis)

## Home automation and platforms

Pick the platform before the device, or you will rebuild the same wheel.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [Home Assistant](https://github.com/home-assistant/core) | :house_with_garden: Open source home automation that puts local control and privacy first. | 91.7k | `Apache-2.0` |
| [Node-RED](https://github.com/node-red/node-red) | Low-code programming for event-driven applications | 23.8k | `Apache-2.0` |
| [ThingsBoard](https://github.com/thingsboard/thingsboard) | All-in-one IoT Platform - Device management, data collection, processing and visualization. | 22.6k | `custom` |
| [EMQX](https://github.com/emqx/emqx) | The most scalable and reliable MQTT broker for AI, IoT, IIoT and connected vehicles | 16.9k | `custom` |
| [ESPHome](https://github.com/esphome/esphome) | ESPHome is a system to control your ESP32, ESP8266, BK72xx, RP2040 by simple yet powerful configuration files and… | 11.9k | `custom` |

<sub>[Back to top](#contents)</sub>

## Firmware and boards

Confirm the exact board revision and your rollback path before flashing.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) | An MCP-based chatbot \| 一个基于MCP的聊天机器人 | 31.8k | `MIT` |
| [Tasmota](https://github.com/arendst/Tasmota) | Alternative firmware for ESP8266 and ESP32 based devices with easy configuration using webUI, OTA updates, automation… | 24.9k | `GPL-3.0` |
| [MicroPython](https://github.com/micropython/micropython) | MicroPython - a lean and efficient Python implementation for microcontrollers and constrained systems | 22.1k | `custom` |
| [QMK Firmware](https://github.com/qmk/qmk_firmware) | Open-source keyboard firmware for Atmel AVR and Arm USB families | 20.8k | `GPL-2.0` |
| [WLED](https://github.com/wled/WLED) | Control WS2812B and many more types of digital RGB LEDs with an ESP32 over WiFi! | 18.9k | `EUPL-1.2` |
| [Arduino ESP32](https://github.com/espressif/arduino-esp32) | Arduino core for the ESP32 family of SoCs | 17.6k | `LGPL-2.1` |
| [Zephyr](https://github.com/zephyrproject-rtos/zephyr) | Primary Git Repository for the Zephyr Project. Zephyr is a new generation, scalable, optimized, secure RTOS for… | 16.9k | `Apache-2.0` |

<sub>[Back to top](#contents)</sub>

## Device UI and toolchain

This layer decides your iteration speed; do not leave it until the hardware is frozen.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [LVGL](https://github.com/lvgl/lvgl) | LVGL is a free, full-featured embedded UI library for devices from small MCUs to 3D-capable MPUs, enhanced by LVGL Pro… | 25.0k | `MIT` |
| [TinyGo](https://github.com/tinygo-org/tinygo) | Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM. | 17.8k | `custom` |
| [PlatformIO](https://github.com/platformio/platformio-core) | Your Gateway to Embedded Software Development Excellence :alien: | 9.6k | `Apache-2.0` |

<sub>[Back to top](#contents)</sub>

## Data and firmware analysis

Once you have many devices, the bottleneck moves from code to data.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [TDengine](https://github.com/taosdata/TDengine) | High-performance, scalable time-series database designed for Industrial IoT (IIoT) scenarios | 25.2k | `AGPL-3.0` |
| [Binwalk](https://github.com/ReFirmLabs/binwalk) | Firmware Analysis Tool | 14.5k | `MIT` |

<sub>[Back to top](#contents)</sub>

## Why this list

IoT lists fill up with schematics and no firmware. Everything here can be flashed, documented or discussed — and the "build a device" track is separated from "just make my home work", so an RTOS is not the entry fee.

## Selection criteria

- A clear use case, a README you can follow and code that runs. No concept-only or demo-video projects.
- Explicit license and a repository that is not archived. Unmaintained projects are flagged and moved out of the main tables.
- One first choice per use case; alternatives sit in the same section for comparison instead of piling up.
- Stars are context, not a verdict. Maintenance cadence, issue response and docs matter more.
- Every line states the problem it solves and who it is for. No copy-pasted marketing copy.

## Contributing

Found a better project, a dead link or a wrong description? Open an issue or send a PR — see [CONTRIBUTING.md](CONTRIBUTING.md). Accepted entries get real stars and license data on the next build.

## About this list

- Stars, licenses and last-commit dates are fetched from the GitHub API at build time — never hand-copied, never stale.
- Adding or dropping a project edits one curated data file; the generator refreshes both languages and all numbers.
- If this saved you from opening a dozen repos, a **star** is the cheapest way to say thanks: [⭐ Star awesome-iot](https://github.com/AwesomeRepoHub/awesome-iot/stargazers)

## License

Content is licensed under [MIT](LICENSE) — reuse freely with attribution. Each project keeps its own copyright and license.

---

<sub>Generated from curated data and the GitHub API. Do not edit directly — see [CONTRIBUTING.md](CONTRIBUTING.md).</sub>

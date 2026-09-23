<div align="center">

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/Deotaland/.github/dev/profile/assets/logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Deotaland/.github/dev/profile/assets/logo-light.svg">
  <img alt="Deotaland" src="https://raw.githubusercontent.com/Deotaland/.github/dev/profile/assets/logo-light.svg" width="600">
</picture>

<br><br>

### Connect any ESP32 device to a production AI agent

[Website](https://deotaland.ai) · [Docs](https://deotaland.cn/#/docs) · [Discussions](https://github.com/Deotaland/Agent_link/discussions)

[![Docs](https://img.shields.io/badge/docs-deotaland.ai-111111)](https://deotaland.cn/#/docs)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/Deotaland/Agent_link/blob/main/LICENSE)
<!-- Discord 徽章先注释掉：shields.io 需要真实 server id，填占位符会渲染成一张报错图
[![Discord](https://img.shields.io/discord/SERVER_ID?label=community&color=5865F2)](DISCORD_URL)
-->

<br>

</div>

---

## What we build

Deotaland runs a hosted agent platform and the open-source firmware that talks to it.
The firmware SDK handles transport, protocol, pairing and OTA, so board code only declares
what hardware it has and fills in a handful of callbacks — the same source builds for BLE or WiFi.

New accounts get free credits, so you can flash a dev board and be talking to an agent
before deciding whether to pay for anything.

## Projects

| Project | What it does |
| --- | --- |
| **[Agent_link](https://github.com/Deotaland/Agent_link)** | Connects ESP32 hardware to the Deotaland agent platform — BLE and WiFi, voice streaming, sensors, OTA |

<sub>Browse [all repositories](https://github.com/orgs/Deotaland/repositories).</sub>

## Start here

1. **Run it** — flash a supported board and pair it from the console

   ```bash
   git clone https://github.com/Deotaland/Agent_link && cd Agent_link/firmware
   idf.py set-target esp32s3 && idf.py menuconfig   # pick your board
   idf.py build flash monitor
   ```

2. **Read the docs** — [deotaland.cn/docs](https://deotaland.cn/#/docs)
3. **Ask a question** — [Discussions](https://github.com/Deotaland/Agent_link/discussions) · found a bug? [open an issue](https://github.com/Deotaland/Agent_link/issues)

<div align="center">
<sub><a href="https://deotaland.ai">deotaland.ai</a></sub>
</div>

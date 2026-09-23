<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/Deotaland/.github/main/profile/assets/logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Deotaland/.github/main/profile/assets/logo-light.svg">
  <img alt="Deotaland" src="https://raw.githubusercontent.com/Deotaland/.github/main/profile/assets/logo-light.svg" width="200">
</picture>
**Connect any ESP32 device to a production AI agent**

[Website](https://deotaland.ai) · [Docs](https://deotaland.cn/#/docs)

[![Docs](https://img.shields.io/badge/docs-deotaland.ai-111111)]({{docs_url}})
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/Deotaland/Agent_link/blob/main/LICENSE)
[![Discord](https://img.shields.io/discord/{{discord_server_id}}?label=community&color=5865F2)]({{discord_url}})

</div>

---

## What we build

Deotaland runs a hosted agent platform and the open-source firmware that talks to it.
The firmware SDK handles transport, protocol, pairing and OTA, so board code only declares
what hardware it has and fills in a handful of callbacks — the same source builds for BLE or WiFi.

New accounts get free credits, so you can flash a dev board and be talking to an agent
before deciding whether to pay for anything.

## Projects

| Project                                                   | What it does                                                                                          |
| --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **[Agent_link](https://github.com/Deotaland/Agent_link)** | Connects ESP32 hardware to the Deotaland agent platform — BLE and WiFi, voice streaming, sensors, OTA |

<sub>更多见 [all repositories](https://github.com/orgs/Deotaland/repositories)。</sub>

## Start here

1. **Run it** — flash a supported board and pair it from the console

   ```bash
   git clone https://github.com/Deotaland/Agent_link && cd Agent_link/firmware
   idf.py set-target esp32s3 && idf.py menuconfig   # pick your board
   idf.py build flash monitor
   ```

2. Read the docs — {{https://deotaland.cn/#/docs}}
3. Ask — Discussions (https://github.com/orgs/Deotaland/discussions)

<div align="center">
<sub><a href="https://deotaland.ai">deotaland.ai</a></sub>
</div>

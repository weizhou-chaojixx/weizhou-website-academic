---
url_pdf: ""
summary: A Universal MCU Firmware Emulator for Dynamic Analysis without Any
  Hardware Dependence
url_video: ""
date: 2021-07-30T00:00:00.000Z
external_link: ""
url_slides: ""
title: Universal IoT Firmware Emulator
tags:
  - firmware
links: []
image:
  caption: uEmu
  focal_point: Smart
  filename: featured.jpg
url_code: "https://github.com/MCUSec/uEmu"
---
Unlike existing MCU firmware dynamic analysis tools that forwards the interactions with unsupported peripherals to the real hardware, μEmu takes the firmware image as input and symbolically executes it by representing unknown peripheral registers as symbols. During symbolic execution, it infers the rules to respond to unknown peripheral accesses. These rules are stored in a knowledge base (KB), which is referred to firmware during dynamic analysis **without any hardware dependence**.

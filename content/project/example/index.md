---
slides: example
url_pdf: ""
summary: ""
url_video: ""
date: 2021-07-30T00:00:00.000Z
external_link: https://github.com/MCUSec/uEmu
url_slides: ""
title: A Universal MCU Firmware Emulator for Dynamic Analysis without Any
  Hardware Dependence
tags:
  - smarthome
links: []
image:
  caption: μEmu
  focal_point: Smart
  filename: 截屏2021-08-21-下午10.34.46.png
url_code: ""
---
Unlike existing MCU firmware dynamic analysis tools that forwards the interactions with unsupported peripherals to the real hardware, μEmu takes the firmware image as input and symbolically executes it by representing unknown peripheral registers as symbols. During symbolic execution, it infers the rules to respond to unknown peripheral accesses. These rules are stored in a knowledge base (KB), which is referred to firmware during dynamic analysis **without any hardware dependence**.
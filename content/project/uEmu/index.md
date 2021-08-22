---
url_pdf: ""
summary: A Universal MCU Firmware Emulator for Dynamic Analysis without Any
  Hardware Dependence
url_video: ""
date: 2021-07-30T00:00:00.000Z
external_link: ""
url_slides: ""
title: IoT Firmware Emulator
tags:
  - firmware
links: []
image:
  caption: uEmu
  focal_point: Smart
  filename: featured.png
url_code: "https://github.com/MCUSec/uEmu"
---
Emulating firmware for microcontrollers is challenging due to the tight coupling between the hardware and firmware. This has greatly impeded the application of dynamic analysis tools to firmware analysis. In this project, we propose and implement a new automatic peripheral modeling approach based on symbolic execution. We take the firmware as input and infers the rules of how to respond to unknown peripheral accesses during symbolic execution. These rules are learned in a knowledge base(KB). With the returned knowledge base, our tool efficiently responds to peripheral read operations during dynamic analysis **without any hardware dependence**. Our tool achieves a passing rate of **95%** in a set of unit tests for peripheral drivers without any manual assistance. We further intergrated Fuzzer (i.e., AFL) on the top of our tool and evaluated more than 20 real-world firmware samples. Evaluation results show that µEmu is capable of emulating real-world ﬁrmware and ﬁnding new bugs. (See more in our [USENIX'21 paper](https://www.usenix.org/system/files/sec21_slides_zhou.pdf)) 

---
title: Identifying Privilege Separation Vulnerabilities in IoT Firmware with Symbolic Execution
publication_types:
  - "1"
authors:
  - Yao Yao
  - admin
  - Yan Jia
  - Lipeng Zhu
  - Peng Liu
  - Yuqing Zhang
publication_short: ""
abstract: With the rapid proliferation of IoT devices, we have witnessed increasing security breaches targeting IoT devices. To address this, considerable attention has been drawn to the vulnerability discovery of IoT firmware. However, in contrast to the traditional firmware bugs/vulnerabilities (e.g. memory corruption), the privilege separation model in IoT firmware has not yet been systematically investigated. In this paper, we conducted an in-depth security analysis of the privilege separation model of IoT firmware and identified a previously unknown vulnerability called privilege separation vulnerability. By combining loading information extraction, library function recognition and symbolic execution, we developed Gerbil, a firmware-analysis-specific extension of the Angr framework for analyzing binaries to effectively identify privilege separation vulnerabilities in IoT firmware. So far, we have evaluated Gerbil on 106 real-world IoT firmware images (100 of which are bare-metal and RTOS-based device firmware. Gerbil have successfully detected privilege separation vulnerabilities in 69 of them. We have also verified and exploited the privilege separation vulnerabilities in several popular smart devices including Xiaomi smart gateway, Changdi smart oven and TP-Link smart WiFi plug. Our research demonstrates that an attacker can leverage the privilege separation vulnerability to launch a border spectrum of attacks such as malicious firmware replacement and denial of service.
draft: false
featured: false
tags: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
publication: *European Symposium on Research in Computer Security 2019 (ESORICS)*, **CCF-B**
date: 2019-09-10T00:00:00.000Z
publishDate: 2019-09-10T00:00:00.000Z

---

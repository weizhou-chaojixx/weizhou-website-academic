---
title: Discovering and understanding the security hazards in the interactions between iot devices, mobile apps, and clouds on smart home platforms
publication_types:
  - "1"
authors:
  - admin
  - Yan Jia
  - Yao Yao
  - Lipeng Zhu
  - Le Guan
  - Yuhang Mao
  - Peng Liu
  - Yuqing Zhang
publication_short: ""
abstract: A smart home connects tens of home devices to the Internet, where an IoT cloud runs various home automation applications. While bringing unprecedented convenience and accessibility, it also introduces various security hazards to users. Prior research studied smart home security from several aspects. However, we found that the complexity of the interactions among the participating entities (i.e., devices, IoT clouds, and mobile apps) has not yet been systematically investigated. In this work, we conducted an in-depth analysis of five widely-used smart home platforms. Combining firmware analysis, network traffic interception, and blackbox testing, we reverse-engineered the details of the interactions among the participating entities. Based on the details, we inferred three legitimate state transition diagrams for the three entities, respectively. Using these state machines as a reference model, we identified a set of unexpected state transitions. To confirm and trigger the unexpected state transitions, we implemented a set of phantom devices to mimic a real device. By instructing the phantom devices to intervene in the normal entity-entity interactions, we have discovered several new vulnerabilities and a spectrum of attacks against real-world smart home platforms.
draft: false
featured: false
tags: []
slides: ""
url_pdf: https://www.usenix.org/system/files/sec19-zhou.pdf
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
publication: "*28th USENIX Security Symposium (Usenix)*, **CCF-A**"
projects:
  - example
date: 2019-08-10T00:00:00.000Z
publishDate: 2019-08-10T00:00:00.000Z

---

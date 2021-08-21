---
title: Automatic Firmware Emulation through Invalidity-guided Knowledge Inference
publication_types:
  - "1"
authors:
  - "**Wei Zhou**"
  - Le Guan
  - Peng Liu
  - Yuqing Zhang
publication_short: ""
abstract: Emulating ﬁrmware for microcontrollers is challenging due to the tight coupling between the hardware and ﬁrmware. This has greatly impeded the application of dynamic analysis tools to ﬁrmware analysis. The state-of-the-artwork automatically models unknown peripherals by observing their access patterns and then leverages heuristics to calculate the appropriate responses when unknown peripheral registers are accessed. However, we empirically found that this approach and the corresponding heuristics are frequently insufﬁcient to emulate ﬁrmware. In this work, we propose a new approach called µEmu to emulate ﬁrmware with unknown peripherals. Unlike existing work that attempts to build a general model for each peripheral, our approach learns how to correctly emulate ﬁrmware execution at individual peripheral access points. It takes the image as input and symbolically executes it by representing unknown peripheral registers as symbols. During symbolic execution, it infers the rules to respond to unknown peripheral accesses. These rules are stored in a knowledge base, which is referred to during the dynamic ﬁrmware analysis. µEmu achieved a passing rate of 95% in a set of unit tests for peripheral drivers without any manual assistance. We also evaluated µEmu with real-world ﬁrmware samples and new bugs were discovered.
draft: false
featured: false
tags: []
slides: ""
url_pdf: "https://www.usenix.org/system/files/sec21-zhou.pdf"
url_slides: "https://www.usenix.org/system/files/sec21_slides_zhou.pdf"
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
publication: 30th USENIX Security Symposium (Usenix), **CCF-A**
projects:
  - example
date: 2021-08-10T00:00:00.000Z

publishDate: 2021-08-10T00:00:00.000Z
url_poster: ""
url_code: "https://github.com/MCUSec/uEmu"
---







---
url_pdf: ""
summary: Discovering and Understanding the Security Hazards in the Interactions between IoT Devices, Mobile Apps, and Clouds on Smart Home Platforms
url_video: ""
date: 2019-07-30T00:00:00.000Z
external_link: ""
url_slides: ""
title: Security Hazards in the Interactions among Smart Home Platforms
tags:
  - smarthome
links: []
image:
  caption: Tested Devices
  focal_point: Smart
  filename: featured.jpg

---
A smart home connects tens of home devices to the Internet, where an IoT cloud runs various home automation applications. While bringing unprecedented convenience and accessibility, it also introduces various security hazards to users. Prior research studied smart home security from several aspects. However, we found that the complexity of the interactions among the participating entities (i.e., devices, IoT clouds, and mobile apps) has not yet been systematically investigated. In this work, we conducted an in-depth analysis of ﬁve widely-used smart home platforms. Combining ﬁrmware analysis, network trafﬁc interception, and blackbox testing, we reverse-engineered the details of the interactions among the participating entities. Based on the details, we inferred three legitimate state transition diagrams for the three entities, respectively. Using these state machines as a reference model, we identiﬁed a set of unexpected state transitions. To conﬁrm and trigger the unexpected state transitions, we implemented a set of phantom devices to mimic a real device. By instructing the phantom devices to intervene in the normal entity-entity interactions, we have discovered several new vulnerabilities and a spectrum of attacks against real-world smart home platforms.

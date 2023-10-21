---
description: How the ecosystem works, how to deploy and more.
cover: >-
  https://images.unsplash.com/photo-1618143416214-16501f28d943?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw3fHxsYXNlcnxlbnwwfHx8fDE2OTY4NjkwMDB8MA&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🏠 About Chroma

Chroma is a computer vision pipeline/engine service made for the _FIRST Robotics Competition_ by a joint effort called Cyclone. Cyclone is comprised of (some) FRC6854 students and alumni to create better and more cost efficient computer vision systems for FRC and beyond.

## So is it like a replacement?

Chroma is not a replacement to current solutions like the Limelight and software like PhotonVision and WPILibPi. Unlike traditional coprocessor software Chroma is only made for selective platforms, and includes features not normally seen in other software. By not supporting certain hardware platforms Chroma is able to have more features with incredible performance.&#x20;

## So what is it made for?

Chroma is made for traditional UVC cameras as well as Stereo (MIPI or UVC) cameras but is most commonly used with inhouse coprocessors made by Cyclone.

## What features does it have?

* [x] Stereo Matching
* [x] Load Balancing
* [x] AprilTags (with Odometry)
* [x] A IDE for configuring pipelines
* [ ] AprilTags with Stereo Acceleration

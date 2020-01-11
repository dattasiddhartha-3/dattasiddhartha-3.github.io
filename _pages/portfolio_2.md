---
permalink: /portfolio_r/
title: ""
excerpt: ""
author_profile: false
---



![image](https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/ciphertext_generation.PNG){: style="float: left"}

### Mask R-CNN object detection to augment human peripheral search

Winning submisson at Cal Hacks 5.0; display goggles that helps Alzheimer’s patients locate personal affects using object detection and speech recognition.
Trained Mask R-CNN object detection classifier on grayed-out ImageNet dataset to sustain realtime inference / classification rate at least 30fps; optimized setup of models (e.g. Yolo v1-3), datasets (e.g. MS Coco) on high-latency Android embedded system
Built Android application and custom scripts (for parsing and relaying camera input) and root-installed into Moverio augmented reality display googles to stream camera input, apply bounding boxes around objects to be detected, and output to display feed of device
Contributed an optimized low-latency embedded-system implementation that performs speech recognition, video streaming/display, image processing with minimal visible stutter

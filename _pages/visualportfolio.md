---
layout: archive
title: "Portfolio"
permalink: /visualportfolio/
author_profile: true
---

#### [YOLO Object Detection to Locate Objects through Speech Recognition](https://dattasiddhartha-3.github.io/portfolio/10000memorypalace/)

<div class="row">
  <div class="column1">
    <img width="200" src="https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/e253ebdepson_goggles_lq.PNG">
  </div>
  <div class="column2">
    <img width="450" src="/images/ba06d3445330501_2205033879773905_1146807820524453888_n.jpg" >
  </div>
  <div class="column3">
    <img width="200" src="/images/moverioimage.PNG">
  </div>
</div>
[video](http://www.youtube.com/watch?v=s6UWctGQRwA)
[code](https://hkustconnect-my.sharepoint.com/personal/sdatta_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley%2FMoverio%2DMemoryPalace%2DInstructions%2Ezip&parent=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley) 
[install instructions](https://drive.google.com/open?id=183nrhzzW63Xrgerxxk8LOU9aBcUO_XZH) 
[slides](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/b524535calhacks_slides.pptx)

_Winning submisson at Cal Hacks 5.0; display goggles that helps Alzheimer’s patients locate personal affects using object detection and speech recognition._

<details>
  <summary> Implementation</summary>
  
  (*) Trained Mask R-CNN object detection classifier on grayed-out ImageNet dataset to sustain realtime inference / classification rate at least 30fps; optimized setup of models (e.g. Yolo v1-3), datasets (e.g. MS Coco) on high-latency Android embedded system
  
  (*) Built Android application and custom scripts (for parsing and relaying camera input) and root-installed into Moverio augmented reality display googles to stream camera input, apply bounding boxes around objects to be detected, and output to display feed of device
  
  (*) Contributed an optimized low-latency embedded-system implementation that performs speech recognition, video streaming/display, image processing with minimal visible stutter
</details>

<details>
  <summary> Domain/application value</summary>
  (*) 
  
  (*) 
</details>

#### [BreakupBot: An Artificial Intelligence Therapeutic Chatbot Conducting Empathetic Counselling via Heartrate Sentimental Analysis](https://dattasiddhartha-3.github.io/portfolio/10001breakupbot/)

 <img src="/images/bb1.png" height="50"> <img src="/images/pipeline.PNG" width="50">

* BreakupBot is a therapeutic chatbot developed to help get over romantic breakups. Organically acquired 200+ users of varying demographics. The system, initially built to help people who could not get over breakups, uses scraped content from dating sites and builds a philosophical counselling knowledge graph as the decision tree for generating responses to user input.


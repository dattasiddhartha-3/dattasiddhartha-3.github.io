---
title: "Memory Palace: YOLO Object Detection to Locate Objects through Speech Recognition"
excerpt: "Winning submisson at Cal Hacks 5.0 (Epson sponsor award). Our team developed a pair of display goggles that helps patients with Alzheimer's or other visual/mental disabilities in locating their personal belongings. Users verbalize the item they are searching for (typically items from the COCO image dataset), and all objects detected would be highlighted."
collection: portfolio
---

Winning submisson at Cal Hacks 5.0 (Epson sponsor award). Our team developed a pair of display goggles that helps patients with Alzheimer's or other visual/mental disabilities in locating their personal belongings. Users verbalize the item they are searching for (typically items from the COCO image dataset), and all objects detected would be highlighted.

<iframe width="560" height="315" src="https://www.youtube.com/embed/s6UWctGQRwA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[code](https://hkustconnect-my.sharepoint.com/personal/sdatta_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley%2FMoverio%2DMemoryPalace%2DInstructions%2Ezip&parent=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley) [installation](https://drive.google.com/open?id=183nrhzzW63Xrgerxxk8LOU9aBcUO_XZH)

### Technical summary

* Trained Mask R-CNN object detection classifier on grayed-out ImageNet dataset to sustain realtime inference / classification rate at least 30fps; optimized setup of models (e.g. Yolo v1-3), datasets (e.g. MS Coco) on high-latency Android embedded system

* Built Android application and custom scripts (for parsing and relaying camera input) and root-installed into Moverio augmented reality display googles to stream camera input, apply bounding boxes around objects to be detected, and output to display feed of device

* Contributed an optimized low-latency embedded-system implementation that performs speech recognition, video streaming/display, image processing with minimal visible stutter

### Motivation

<img src="https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/e253ebdepson_goggles_lq.PNG" width="360">

This is what the user sees.

Over 24 hours our team built the embedded system that would permit Epson's Moverio goggles to detect specific objects for users. This included setting up voice recognition input for object commands, relaying the image from the goggles to a server PC, running an object detection system on the PC, and relaying the image in real-time back to the goggles. The object detection system was based on a Mask RCNN model trained on a modified image dataset. 

<img src="/images/ba06d3445330501_2205033879773905_1146807820524453888_n.jpg" width="360">

Completion of the object detection system backend: 

<img src="/images/moverioimage.PNG" width="360">

Preview of my teammate testing the goggles out in real-time, while my PC displays what he is seeing (Click the [video]((http://www.youtube.com/watch?v=s6UWctGQRwA)) to watch):

[Hackathon submission](https://calhacks5.hackerearth.com/sprints/cal-hacks-50/dashboard/b436967/submission/) [slides](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/b524535calhacks_slides.pptx) [Recount on Cal Hacks](http://www.zacharychaoportfolio.com/blog/calhacks)


---
layout: archive
title: "Portfolio"
permalink: /visualportfolio/
author_profile: true
---

### [Mask R-CNN object detection to augment human peripheral search](https://dattasiddhartha-3.github.io/portfolio/10000memorypalace/)

<img width="150" src="https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/e253ebdepson_goggles_lq.PNG"> <img width="350" src="/images/ba06d3445330501_2205033879773905_1146807820524453888_n.jpg" > <img width="150" src="/images/moverioimage.PNG">

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



### [Execution of philosophical counselling through knowledge graphing, natural language processing, and sentiment approximation](https://dattasiddhartha-3.github.io/portfolio/10001breakupbot/)

<img width="150" src="/images/bb1.png"> <img width="400" src="/images/pipeline.PNG" > <img width="200" src="/images/Inkedbb2_LI.jpg">

[video](https://www.youtube.com/embed/1NxWMQA7tlM)
[paper](https://drive.google.com/file/d/142kTVrKNGH42splekvbfXGVtT9HhNQPq/view)
[poster](https://drive.google.com/open?id=0Bya0t6OLDU2FNTV2S2NKTmpMSHc)

_BreakupBot, a therapeutic chatbot to recuperate from romantic breakups, organically acquired 200+ users of varying demographics within first week._

<details>
  <summary> Implementation</summary>
  
  (*) Built Android application and JSON-based API that receives user text input and returns counselling-based responses
  
  
  (*) Based on real-time user variables (lover type, heartrate-sentiment approximation), categorized text corpus is filtered before running hidden markov chain text generator
  
  
  (*) Use random forest classification model and hierarichal clustering to bucket users into John A. Lee's six types of lovers based on preliminary text input
  
  
  (*) Adopted script that estimates heartrate from camera image input based on measurement of signal peak difference at time intervals
  
  
  (*) Scripted web scrapers to pull high-rated responses from love-related forums; constructed knowledge graph from corpora to facilitate filtering for text generator


</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) 
  
  (*) 
</details>


### [Automated source code obfuscation and privacy-preserving execution through sequence-to-sequence networks](https://dattasiddhartha-3.github.io/portfolio/10002doc/)

<img width="250" src="/images/ciphertext_generation.PNG"> <img width="250" src="/images/key_generation.PNG" > <img width="250" src="/images/execution.PNG" >

[pdf](https://arxiv.org/pdf/1909.01837.pdf)

_Contributed (1) quantitative framework for evaluating obfuscated code; (2) privacy-preserving system that uses seq2seq models to obfuscate plaintext and execute obfuscated ciphertext. _

<details>
  <summary> Implementation</summary>
  
  (*) 
  
  (*) 
  
  (*) 

</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) 
  
  (*) 
</details>

---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/Q11_R_vP8iDYi8VD6heNj_Compressed_4.png
excerpt: >
  A young, aspiring computational scientist with the ambition to design new tools to solve larger problems.<br />
feature_row:

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

_Contributed (1) quantitative framework for evaluating obfuscated code; (2) privacy-preserving system that uses seq2seq models to obfuscate plaintext and execute obfuscated ciphertext. Submitted to ICASSP 2020_

<details>
  <summary> Implementation</summary>
  
  (*) Implemented reversible character-embedded encoder-decoder model that takes plaintext input, recursively generates obfuscated code to ensure the execution program can run the obfiscated code without error, then returns obfuscated code, h5 model files, and  char/word-to-index dictionaries
  
  (*) Set up experimental pipeline to obfuscate benchmark source code, and compare/plot defined metrics between benchmark obfuscated and seq2seq obfuscated code
  

</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) 
  
  (*) 
</details>

### [Motif detection and clustering of franchise location network graphs](https://dattasiddhartha-3.github.io/portfolio/10002locationfingerprinting/)

<img width="250" src="/images/fingerprint.PNG"> <img width="450" src="/images/fingerprint2.PNG" >

[code](https://github.com/dattasiddhartha-1/Berkeley-Demand-Enterprises)

[slides](https://drive.google.com/open?id=1aOQiZsVpe2V5yjKr-_aAqeqCny1E2izo)

_Clustering network motifs of successful franchise locations, to consequently identify franchise expansion patterns._

<details>
  <summary> Implementation</summary>
  
  (*) Hybrid implementation of motif-detection, bridge-detection, and clustering algorithms to yield sequential coordinates of geographical locations depending on category of product/business, based on network de-anonymization framework
  
  (*) Developed REST API to run algorithm and pass JSON-formatted output to Ruby on Rails frontend
  
  (*) Contributions of this work in the use of network graphs in time-independent pattern interpolation, recursive backtesting method of running/validating the motifs through training/testing franchises
  

</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) The project holds value from a geographical information systems (GIS) or operations perspective, as it autonomously generates expansion patterns, including non-obvious ones. This would aid newly-developed companies to expand their businesses in a structured way that had "proven" to succeed.
  
  (*) 
</details>

### [GAN-MC simulation for HIV sequence prediction](https://dattasiddhartha-3.github.io/portfolio/10003haiv/)

<img width="350" src="/images/haiv5.PNG"> <img width="400" src="/images/haiv4.PNG" >

[paper](https://drive.google.com/open?id=1UwI3d3BeTJiHmEiT8r4QizsMBvl6ONaI)

[poster](https://drive.google.com/open?id=1kv3ASC_jhFq8qyhGdLw87ZcuxMC8Dpnu)

_Predicting future HIV sequences given initial strains through use of Monte Carlo in mutation, and generative adversarial networks to prune predictions._

<details>
  <summary> Implementation</summary>
  
  (*) Applied mutations (addition, substitution, etc) through Monte Carlo upon listed initial strain sequences (source: Stanford HIV database); built adversarial network to generate adversarial sequences, and discriminator/classification network to identify valid subsequent sequences to prune MC-mutations
  

</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) Further contribution of providing a mutation prediction algorithm is classifying HIV antiretroviral medication for specific strains of HIV, thus optimizing medication intake for patients in terms of viral drig resistance and elimination of virus
  
  (*) 
  
</details>

### [Instrumental note generation through object-impact detection](https://dattasiddhartha-3.github.io/portfolio/10004armusic/)

<img width="350" src="/images/armusic.png">

[code](https://bit.ly/2P7YYRQ)

[video](https://bit.ly/2GcKUCl)

[video](https://bit.ly/2UY9FM0)

_Synthesis of musical notes based on tapping food with utensils, with each dish assigned to a different instrument._

<details>
  <summary> Implementation</summary>
  
  (*) Trained Resnet and Yolo object detection models on labelled food images; paired food categories with instruments, and sub-categories with different notes, and encoded x-axis location across the sub-category image with distinct notes
  
  (*) Trained separate object detection model to identify utensils, and calculate proximity between utensils and food item (distance~0 infers impact)
  
  (*) Human-computer interaction contribution in terms of augmenting a dining experience with sound, visuals and physical action.
  

</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) 
  
  (*) 
  
  
### [](https://dattasiddhartha-3.github.io/portfolio/10004armusic/)

<img width="350" src="/images/armusic.png">

[code](https://bit.ly/2P7YYRQ)

[video](https://bit.ly/2GcKUCl)

[video](https://bit.ly/2UY9FM0)

_Synthesis of musical notes based on tapping food with utensils, with each dish assigned to a different instrument._

<details>
  <summary> Implementation</summary>
  
  (*) Trained Resnet and Yolo object detection models on labelled food images; paired food categories with instruments, and sub-categories with different notes, and encoded x-axis location across the sub-category image with distinct notes
  
  (*) Trained separate object detection model to identify utensils, and calculate proximity between utensils and food item (distance~0 infers impact)
  
  (*) Human-computer interaction contribution in terms of augmenting a dining experience with sound, visuals and physical action.
  

</details>

<details>
  <summary> Domain/application value</summary>
  
  (*) 
  
  (*) 
  
</details>

---

{% include feature_row %}

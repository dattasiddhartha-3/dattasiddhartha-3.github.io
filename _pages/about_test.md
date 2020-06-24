---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/github%20dashboard.jpg
excerpt: >
  A young computational scientist testing the waters of the future one project at a time.<br />

feature_row:

  - image_path: https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/e253ebdepson_goggles_lq.PNG
    alt: "customizable"
    title: "Mask R-CNN object detection to augment human peripheral search"
    excerpt: "
    Winning submisson at Cal Hacks 5.0; display goggles that helps Alzheimer’s patients locate personal affects using object detection and speech recognition.\n
    
    > [[video]](http://www.youtube.com/watch?v=s6UWctGQRwA) 
[[code]](https://hkustconnect-my.sharepoint.com/:u:/g/personal/sdatta_connect_ust_hk/EaXFuzpiDpVAuHYkYNxf-G0BoaVhGvKZyD_tqhV3OqkeEw?e=UhZdVt) 
[[install instructions]](https://drive.google.com/open?id=183nrhzzW63Xrgerxxk8LOU9aBcUO_XZH) 
[[slides]](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/b524535calhacks_slides.pptx)\n
    
   > Trained Mask R-CNN object detection classifier on grayed-out ImageNet dataset to sustain realtime inference / classification rate at least 30fps; optimized setup of models (e.g. Yolo v1-3), datasets (e.g. MS Coco) on high-latency Android embedded system\n
  
  > Built Android application and custom scripts (for parsing and relaying camera input) and root-installed into Moverio augmented reality display googles to stream camera input, apply bounding boxes around objects to be detected, and output to display feed of device \n
  
  > Contributed an optimized low-latency embedded-system implementation that performs speech recognition, video streaming/display, image processing with minimal visible stutter
"
    url: "https://dattasiddhartha-3.github.io/portfolio/10000memorypalace/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
    
  - image_path: http://img.youtube.com/vi/1NxWMQA7tlM/0.jpg
    alt: "fully responsive"
    title: "Execution of philosophical counselling through knowledge graphing, natural language processing, and sentiment approximation"
    excerpt: "
    BreakupBot, a therapeutic chatbot to recuperate from romantic breakups, organically acquired 200+ users of varying demographics within first week.\n
    
    > [[app]](https://drive.google.com/open?id=1AVUpfepD_4yhdqv5L16C0XYDfLBk88om) 
      [[code]](https://github.com/dattasiddhartha-4/breakup-bot/) 
      [[video]](https://www.youtube.com/embed/1NxWMQA7tlM) 
      [[paper]](https://drive.google.com/file/d/142kTVrKNGH42splekvbfXGVtT9HhNQPq/view) 
      [[poster]](https://drive.google.com/open?id=0Bya0t6OLDU2FNTV2S2NKTmpMSHc)\n

   > Built Android application and JSON-based API that receives user text input and returns counselling-based responses\n
  
  
  > Based on real-time user variables (lover type, heartrate-sentiment approximation), categorized text corpus is filtered before running hidden markov chain text generator\n
  
  
  > Use random forest classification model and hierarichal clustering to bucket users into John A. Lee's six types of lovers based on preliminary text input\n
  
  
  > Adopted script that estimates heartrate from camera image input based on measurement of signal peak difference at time intervals\n
  
  
  > Scripted web scrapers to pull high-rated responses from love-related forums; constructed knowledge graph from corpora to facilitate filtering for text generator
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10001breakupbot/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
 
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/armusic.png
    alt: "100% fre4e"
    title: "Instrumental note generation through object-impact detection"
    excerpt: "
    Synthesis of musical notes based on tapping food with utensils, with each dish assigned to a different instrument.\n
    
    > [[code]](https://bit.ly/2P7YYRQ) 
[[video]](https://bit.ly/2GcKUCl) 
[[video]](https://bit.ly/2UY9FM0)\n

> Trained Resnet and Yolo object detection models on labelled food images; paired food categories with instruments, and sub-categories with different notes, and encoded x-axis location across the sub-category image with distinct notes\n
  
  > Trained separate object detection model to identify utensils, and calculate proximity between utensils and food item (distance~0 infers impact)\n
  
  > Human-computer interaction contribution in terms of augmenting a dining experience with sound, visuals and physical action.
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10004armusic/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/dp_arcchitecture.jpg
    alt: "100% free2"
    title: "Inductive inference of decision-making motifs from trade execution networks"
    excerpt: "Prediction of client trade execution through application of reinforcement learning in rational agent decision-making \n
    
    > [[architecture]](https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/dp_arcchitecture.jpg) \n

    > Client inferencing engine built for an investment bank; maps out traders to stocks with 70+ markets/cognitive features to interpolate trade execution motifs \n

    > Network graph between clients and stocks: client-client edges were weighted functions of client-specific properties (e.g. fund type); stock-stock edges on stock-specific properties (e.g. sector, average daily volume); client-stock edges on behavioural/decision-making/trading features (e.g. likelihood of traded with volatility, risk aversity relative to news, momentum/contrarian, preferences for certain sectors, regret minimization, confidence bias) \n

   > Edge weight matrices were calculated using reinforcement learning based on historical trades taken by each client on each stock \n

   > Output was the identification of cognitive decision-making motifs adopted by each individual trader relative to other traders, and even able to identify successful situation-specific motifs based on the cumulative profit made by those cognitive motifs (i.e. clustered different decision-making motifs to specific scenarios/environments) \n

   > Back-testing indicated ~7x% accuracy in predicting client execution on any given day (accuracy rising exponentially as time horizon increases to 2 weeks); successfully captured value-based decision-making cognition of rational agents
    "

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/ciphertext_generation.PNG
    alt: "100% free"
    title: "Automated source code obfuscation and privacy-preserving execution through sequence-to-sequence networks"
    excerpt: "
    Contributed (1) quantitative framework for evaluating obfuscated code; (2) privacy-preserving system that uses seq2seq models to obfuscate plaintext and execute obfuscated ciphertext.\n
    
    > [[arXiv]](https://arxiv.org/pdf/1909.01837.pdf)\n
    
    > Implemented reversible character-embedded encoder-decoder model that takes plaintext input, recursively generates obfuscated code to ensure the execution program can run the obfiscated code without error, then returns obfuscated code, h5 model files, and  char/word-to-index dictionaries\n
  
  > Set up experimental pipeline to obfuscate benchmark source code, and compare/plot defined metrics between benchmark obfuscated and seq2seq obfuscated code"
    url: "https://dattasiddhartha-3.github.io/portfolio/10002doc/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     

---

### Siddhartha Datta

This is mostly a snapshot of my thoughts and work, just a personal repository.

## Highlighted projects

{% include feature_row %}


###### Last updated: 24/06/2020 | [Archived projects](https://dattasiddhartha-3.github.io/portfolio/achived_projects/)

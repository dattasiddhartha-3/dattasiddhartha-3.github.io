---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/Q11_R_vP8iDYi8VD6heNj_Compressed_4.png
excerpt: >
  A young, aspiring computational scientist with the ambition to design new tools to solve larger problems.<br />
feature_row:

  - image_path: https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/e253ebdepson_goggles_lq.PNG
    alt: "customizable"
    title: "Mask R-CNN object detection to augment human peripheral search"
    excerpt: "
    Winning submisson at Cal Hacks 5.0; display goggles that helps Alzheimer’s patients locate personal affects using object detection and speech recognition.
    
    Trained Mask R-CNN object detection classifier on grayed-out ImageNet dataset to sustain realtime inference / classification rate at least 30fps; optimized setup of models (e.g. Yolo v1-3), datasets (e.g. MS Coco) on high-latency Android embedded system
  
  Built Android application and custom scripts (for parsing and relaying camera input) and root-installed into Moverio augmented reality display googles to stream camera input, apply bounding boxes around objects to be detected, and output to display feed of device
  
  Contributed an optimized low-latency embedded-system implementation that performs speech recognition, video streaming/display, image processing with minimal visible stutter
"
    url: "https://dattasiddhartha-3.github.io/portfolio/10000memorypalace/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
    
  - image_path: http://img.youtube.com/vi/1NxWMQA7tlM/0.jpg
    alt: "fully responsive"
    title: "
    BreakupBot, a therapeutic chatbot to recuperate from romantic breakups, organically acquired 200+ users of varying demographics within first week.
    
    Built Android application and JSON-based API that receives user text input and returns counselling-based responses
  
  
  Based on real-time user variables (lover type, heartrate-sentiment approximation), categorized text corpus is filtered before running hidden markov chain text generator
  
  
  Use random forest classification model and hierarichal clustering to bucket users into John A. Lee's six types of lovers based on preliminary text input
  
  
  Adopted script that estimates heartrate from camera image input based on measurement of signal peak difference at time intervals
  
  
  Scripted web scrapers to pull high-rated responses from love-related forums; constructed knowledge graph from corpora to facilitate filtering for text generator
    
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10001breakupbot/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
    
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/ciphertext_generation.PNG
    alt: "100% free"
    title: "Automated source code obfuscation and privacy-preserving execution through sequence-to-sequence networks"
    excerpt: "Contributed (1) quantitative framework for evaluating obfuscated code; (2) privacy-preserving system that uses seq2seq models to obfuscate plaintext and execute obfuscated ciphertext. Submitted to ICASSP 2020
    
    Implemented reversible character-embedded encoder-decoder model that takes plaintext input, recursively generates obfuscated code to ensure the execution program can run the obfiscated code without error, then returns obfuscated code, h5 model files, and  char/word-to-index dictionaries
  
  Set up experimental pipeline to obfuscate benchmark source code, and compare/plot defined metrics between benchmark obfuscated and seq2seq obfuscated code"
    url: "https://dattasiddhartha-3.github.io/portfolio/10002doc/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/fingerprint.PNG
    alt: "100% free2"
    title: "Motif detection and clustering of franchise location network graphs"
    excerpt: "Clustering network motifs of successful franchise locations, to consequently identify franchise expansion patterns.
    
     Hybrid implementation of motif-detection, bridge-detection, and clustering algorithms to yield sequential coordinates of geographical locations depending on category of product/business, based on network de-anonymization framework
  
  Developed REST API to run algorithm and pass JSON-formatted output to Ruby on Rails frontend
  
  Contributions of this work in the use of network graphs in time-independent pattern interpolation, recursive backtesting method of running/validating the motifs through training/testing franchises
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10002locationfingerprinting/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/haiv5.PNG
    alt: "100% fre3e"
    title: "HAIV: Computational Precision Medicine against HIV Drug Resistance"
    excerpt: "A mutation prediction algorithm built to map out subsequent mutations of a strain of HIV virus in a person's bloodstream over n timesteps, and can be further used in optimizing antiretroviral treatment (allocating the right medication at the right time to avoid drug resistance)."
    url: "https://dattasiddhartha-3.github.io/portfolio/10003haiv/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/armusic.png
    alt: "100% fre4e"
    title: "Music Generation through Food Detection, Assignment of Music Notes to Distinct Items, and Utensil Impact Detection"
    excerpt: "An AR system where users put on a pair of goggles or a visualizer above highlights the food on the table, and users use their utensils to generate individualized music notes from tapping their food."
    url: "https://dattasiddhartha-3.github.io/portfolio/10004armusic/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
    
---

{% include feature_row %}


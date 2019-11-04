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
    Winning submisson at Cal Hacks 5.0; display goggles that helps Alzheimer’s patients locate personal affects using object detection and speech recognition.\n
    
    > [video](http://www.youtube.com/watch?v=s6UWctGQRwA) 
[code](https://hkustconnect-my.sharepoint.com/personal/sdatta_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley%2FMoverio%2DMemoryPalace%2DInstructions%2Ezip&parent=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley) 
[install instructions](https://drive.google.com/open?id=183nrhzzW63Xrgerxxk8LOU9aBcUO_XZH) 
[slides](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/b524535calhacks_slides.pptx)\n
    
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
    
    > [video](https://www.youtube.com/embed/1NxWMQA7tlM) 
[paper](https://drive.google.com/file/d/142kTVrKNGH42splekvbfXGVtT9HhNQPq/view) 
[poster](https://drive.google.com/open?id=0Bya0t6OLDU2FNTV2S2NKTmpMSHc)\n
    
   > Built Android application and JSON-based API that receives user text input and returns counselling-based responses\n
  
  
  > Based on real-time user variables (lover type, heartrate-sentiment approximation), categorized text corpus is filtered before running hidden markov chain text generator\n
  
  
  > Use random forest classification model and hierarichal clustering to bucket users into John A. Lee's six types of lovers based on preliminary text input\n
  
  
  > Adopted script that estimates heartrate from camera image input based on measurement of signal peak difference at time intervals\n
  
  
  > Scripted web scrapers to pull high-rated responses from love-related forums; constructed knowledge graph from corpora to facilitate filtering for text generator
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10001breakupbot/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
    
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/ciphertext_generation.PNG
    alt: "100% free"
    title: "Automated source code obfuscation and privacy-preserving execution through sequence-to-sequence networks"
    excerpt: "Contributed (1) quantitative framework for evaluating obfuscated code; (2) privacy-preserving system that uses seq2seq models to obfuscate plaintext and execute obfuscated ciphertext. Submitted to ICASSP 2020\n
    
    > [pdf](https://arxiv.org/pdf/1909.01837.pdf)\n
    
    > Implemented reversible character-embedded encoder-decoder model that takes plaintext input, recursively generates obfuscated code to ensure the execution program can run the obfiscated code without error, then returns obfuscated code, h5 model files, and  char/word-to-index dictionaries
  
  > Set up experimental pipeline to obfuscate benchmark source code, and compare/plot defined metrics between benchmark obfuscated and seq2seq obfuscated code"
    url: "https://dattasiddhartha-3.github.io/portfolio/10002doc/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/fingerprint.PNG
    alt: "100% free2"
    title: "Motif detection and clustering of franchise location network graphs"
    excerpt: "Clustering network motifs of successful franchise locations, to consequently identify franchise expansion patterns.\n
    
    > [code](https://github.com/dattasiddhartha-1/Berkeley-Demand-Enterprises) 
    [slides](https://drive.google.com/open?id=1aOQiZsVpe2V5yjKr-_aAqeqCny1E2izo)\n
    
     > Hybrid implementation of motif-detection, bridge-detection, and clustering algorithms to yield sequential coordinates of geographical locations depending on category of product/business, based on network de-anonymization framework\n
  
  > Developed REST API to run algorithm and pass JSON-formatted output to Ruby on Rails frontend\n
  
  > Contributions of this work in the use of network graphs in time-independent pattern interpolation, recursive backtesting method of running/validating the motifs through training/testing franchises\n
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10002locationfingerprinting/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/haiv5.PNG
    alt: "100% fre3e"
    title: "GAN-MC simulation for HIV sequence prediction"
    excerpt: "
    Predicting future HIV sequences given initial strains through use of Monte Carlo in mutation, and generative adversarial networks to prune predictions.\n
    
    > [paper](https://drive.google.com/open?id=1UwI3d3BeTJiHmEiT8r4QizsMBvl6ONaI) 
[poster](https://drive.google.com/open?id=1kv3ASC_jhFq8qyhGdLw87ZcuxMC8Dpnu)\n

> Applied mutations (addition, substitution, etc) through Monte Carlo upon listed initial strain sequences (source: Stanford HIV database); built adversarial network to generate adversarial sequences, and discriminator/classification network to identify valid subsequent sequences to prune MC-mutations\n
> Further contribution of providing a mutation prediction algorithm is classifying HIV antiretroviral medication for specific strains of HIV, thus optimizing medication intake for patients in terms of viral drig resistance and elimination of virus
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10003haiv/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/armusic.png
    alt: "100% fre4e"
    title: "Instrumental note generation through object-impact detection"
    excerpt: "Synthesis of musical notes based on tapping food with utensils, with each dish assigned to a different instrument.\n
    
    > [code](https://bit.ly/2P7YYRQ) 
[video](https://bit.ly/2GcKUCl) 
[video](https://bit.ly/2UY9FM0)\n

> Trained Resnet and Yolo object detection models on labelled food images; paired food categories with instruments, and sub-categories with different notes, and encoded x-axis location across the sub-category image with distinct notes\n
  
  > Trained separate object detection model to identify utensils, and calculate proximity between utensils and food item (distance~0 infers impact)\n
  
  > Human-computer interaction contribution in terms of augmenting a dining experience with sound, visuals and physical action.
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10004armusic/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
    
    
 - image_path: https://i1.wp.com/data-x.blog/wp-content/uploads/2018/12/Brain-Poster-Aditya-Goel-page-001.jpg?zoom=2&resize=2000%2C1200&ssl=1
    alt: "100% fre5e"
    title: "Value-based decision-making predictions through time-series ECoG signal models"
    excerpt: "Predicting likelihood to act or not to act through computational models based on (i) expected value to gain and (ii) neural ECoG signals.\n
    
    > [code](https://github.com/dattasiddhartha/DataX-NeuralDecisionMaking) 
      [poster](https://data-x.blog/projects/predicting-gambling-decisions/) 
      [data](https://crcns.org/data-sets/ofc/ofc-3/about-ofc-2)\n

    > Built deep learning models (multilayer perceptron, LSTM, R-CNN) with Pytorch to generate ECoG decision-making distributions and prediction of decision classification based on initial ECoG and potential gainable values\n
  
   > Built visualization functions to plot MATLAB-stored ECoG signals recorded from epilepsy patients performing gambling tasks
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/20010schoolproj/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
    
    
 - image_path: https://raw.githubusercontent.com/dattasiddhartha-1/polysemous-word-tagging-tool/master/screenshot_preview.PNG
    alt: "100% fre6e"
    title: "Definition and word property tagging web application for word polysemy"
    excerpt: "Tag words of multiple definitions to study concept/word learning among children.\n
    
    > [code](https://github.com/dattasiddhartha-1/polysemous-word-tagging-tool/tree/master)\n

    > Loaded corpora from childes-db, loaded tagging functions and text data from SemCor, built interactive tool using JavaScript and jquery for users on Mechanical Turk to tag polysemous words, in order to develop computational models around chidren concept learning
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/20010schoolproj/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
    
---

{% include feature_row %}


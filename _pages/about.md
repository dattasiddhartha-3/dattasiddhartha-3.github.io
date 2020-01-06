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
[[code]](https://hkustconnect-my.sharepoint.com/personal/sdatta_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley%2FMoverio%2DMemoryPalace%2DInstructions%2Ezip&parent=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley) 
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
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/sachacks.PNG
    alt: "100% fre4e"
    title: "Automated 911 and positioning system triggered by weapon detection"
    excerpt: "
    Uses dashcams on cars to detect weapons being used in crimes and automatically making calls to the police. \n
    
    > [[video]](https://drive.google.com/file/d/1EOl4VYuxbt7_6Gz5KzhhcyGd_sdb3nG6/view?fbclid=IwAR1IgvE1oLZFLLLfAUU1ePDtXjmmFULMciBeDlq23GcWMTbaXXktjjsEGO0) [[slides]](https://drive.google.com/file/d/18XjwReayYjx8WDMM-l4k_HvLPWb57gW5/view?fbclid=IwAR16UxXIYthOsgbZGkYapLnIUXhxG3KFrVRW3TQDVHsx3eN_LOPMrSKTo2c) [[demo]](https://sachacks.herokuapp.com/)\n
    
    > Identifying crime: used Inception v2 R-CNN trained on a weapons dataset; idea was to place cameras in each car in the network, and use model to run real time inference to detect suspicious activity \n
    
    > Notifying the network: retrieve car's geolocation, odometer, locking all surrounding cars using SmartCar's API and sending out an SMS using Twillio and NoonLight when a threat was detected by the model. For this they used  which gave us access to the car's GPS, odometer and locking mechanisms; used Flask to build web app, Google Cloud Platform's Map API and JavaScript to visualize the crime data, Ethereum's API to access the ledger and Twitter's bootstrap for CSS, so when crime data was pushed to the database it would be visualized as each clickable dot displays the frame which set the model off as well as the location and time \n
    
    > Rewarding cars: set up smart contracts with Ethereum, letting users and companies alike put up rewards \n

    > Won SacHacks 2018 as well as sponsor award from Smartcar
    "
    
feature_row2:

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
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/fingerprint.PNG
    alt: "100% free2"
    title: "Motif detection and clustering of franchise location network graphs"
    excerpt: "Clustering network motifs of successful franchise locations, to consequently identify franchise expansion patterns.\n
    
    > [[code]](https://github.com/dattasiddhartha-1/Berkeley-Demand-Enterprises) 
    [[slides]](https://drive.google.com/open?id=1aOQiZsVpe2V5yjKr-_aAqeqCny1E2izo)\n
    
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
    
    > [[paper]](https://drive.google.com/open?id=1UwI3d3BeTJiHmEiT8r4QizsMBvl6ONaI) 
[[poster]](https://drive.google.com/open?id=1kv3ASC_jhFq8qyhGdLw87ZcuxMC8Dpnu)\n

> Applied mutations (addition, substitution, etc) through Monte Carlo upon listed initial strain sequences (source: Stanford HIV database); built adversarial network to generate adversarial sequences, and discriminator/classification network to identify valid subsequent sequences to prune MC-mutations\n

> Further contribution of providing a mutation prediction algorithm is classifying HIV antiretroviral medication for specific strains of HIV, thus optimizing medication intake for patients in terms of viral drig resistance and elimination of virus
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/10003haiv/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
        
  - image_path: https://i1.wp.com/data-x.blog/wp-content/uploads/2018/12/Brain-Poster-Aditya-Goel-page-001.jpg?zoom=2&resize=2000%2C1200&ssl=1
    alt: "100% fre4e"
    title: "Value-based decision-making predictions through time-series ECoG signal models"
    excerpt: "
    Predicting likelihood to act or not to act through computational models based on (i) expected value to gain and (ii) neural ECoG signals.\n
    
    > [[code]](https://github.com/dattasiddhartha/DataX-NeuralDecisionMaking) 
      [[poster]](https://data-x.blog/projects/predicting-gambling-decisions/) 
      [[data]](https://crcns.org/data-sets/ofc/ofc-3/about-ofc-2)\n

> Built deep learning models (multilayer perceptron, LSTM, R-CNN) with Pytorch to generate ECoG decision-making distributions and prediction of decision classification based on initial ECoG and potential gainable values\n
  
   > Built visualization functions to plot MATLAB-stored ECoG signals recorded from epilepsy patients performing gambling tasks
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/20010schoolproj/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
    
    
feature_row3:

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/ciphertext_generation.PNG
    alt: "100% free"
    title: "Automated source code obfuscation and privacy-preserving execution through sequence-to-sequence networks"
    excerpt: "
    Contributed (1) quantitative framework for evaluating obfuscated code; (2) privacy-preserving system that uses seq2seq models to obfuscate plaintext and execute obfuscated ciphertext. Submitted to ICASSP 2020\n
    
    > [[arXiv]](https://arxiv.org/pdf/1909.01837.pdf)\n
    
    > Implemented reversible character-embedded encoder-decoder model that takes plaintext input, recursively generates obfuscated code to ensure the execution program can run the obfiscated code without error, then returns obfuscated code, h5 model files, and  char/word-to-index dictionaries\n
  
  > Set up experimental pipeline to obfuscate benchmark source code, and compare/plot defined metrics between benchmark obfuscated and seq2seq obfuscated code"
    url: "https://dattasiddhartha-3.github.io/portfolio/10002doc/"
    btn_class: "btn--primary"
    btn_label: "Learn more"     
  
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/WhatsApp%20Image%202019-11-19%20at%2007.38.53.jpeg
    alt: "100% free"
    title: "Adversarial attack optimization against crossdomain classification models"
    excerpt: "
    Contributed a new adversarial attack architecture against text classification models; notable differences in this model is that it is a complete black-box attack, and uses features of domain adaptation. Submitted to ACL 2020\n
    
    > [[brief]](https://drive.google.com/open?id=1O5hYeC3roV7LVDLaCoXXFBqwLPmykK9oP0kNpe-LXGQ)\n
    
    > Transferred over implementations of FGSM, Random-FGSM and Basic Iterative Method (BIM) from continuous image space over to the text space to apply perturbations to sentences.\n
  
  > Designed expertimental pipeline to optimize for certain variables (attack algorithm, domains, model architectures, etc) to locate optimal variables to attack a certain victim architecture, and narroweed down on the variable we should use to construct an attack architecture"


feature_row4:

  - image_path: https://raw.githubusercontent.com/dattasiddhartha/neurocogpy/master/images/ts_image.PNG
    alt: "100% fre3e"
    title: "neurocogpy"
    excerpt: "
    Open-sourced electrophysiological signal visualization library built for Python\n
    
    > [[library]](https://github.com/dattasiddhartha/neurocogpy)\n

    > Defined modules/functions for general-purpose data processing, analysis and modeling of ECoG signal data, including parsing of MATLAB files into Python, different feature engineering techniques for multi-electrode time series data, different visualization techniques, and pre-built class-based decision-making classification models
    "
    url: "https://github.com/dattasiddhartha/neurocogpy"
    btn_class: "btn--primary"
    btn_label: "Learn more"
    

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-1/polysemous-word-tagging-tool/master/screenshot_preview.PNG
    alt: "100% fre4e"
    title: "Definition and word property tagging web application for word polysemy"
    excerpt: "
    Tag words of multiple definitions to study concept/word learning among children.\n
    
    > [[code]](https://github.com/dattasiddhartha-1/polysemous-word-tagging-tool/tree/master)\n

    > Loaded corpora from childes-db, loaded tagging functions and text data from SemCor, built interactive tool using JavaScript and jquery for users on Mechanical Turk to tag polysemous words, in order to develop computational models around chidren concept learning
    "
    url: "https://dattasiddhartha-3.github.io/portfolio/20010schoolproj/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 
    
    
  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/UI.PNG
    alt: "100% fre4e"
    title: "Inter-language Grammar Error Correction: Correction platform + GEC algorithms"
    excerpt: "
    Automated GEC system to grade grammatical integrity of student essays and aid non-native English writers learn from Chinese-specific inter-language errors. \n
    
    > Built transformer models, error-specific character-embedded and word-embedded sequence-to-sequence models, general-error hidden markov models, and hard-coded error models to implement a general-purpose language correction system for the Linguistics department, HKUST \n
    
    > Built a GUI for faculty members to enter errors to build training set \n

    > Contribution in building models that targets passive voice errors (with sentence-to-sentence seq2seq to infer context in markov model active-passive conversion) and interlanguage errors made by Chinese students, pending publication
    "
    

    
feature_row5:    

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/winnings.PNG
    alt: "100% fre4e"
    title: "Past Hackathon Winnings/Submission"
    excerpt: ""
    url: "https://dattasiddhartha-3.github.io/portfolio/20000hackathons/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/school2.PNG
    alt: "100% fre4e"
    title: "Past School Projects"
    excerpt: ""
    url: "https://dattasiddhartha-3.github.io/portfolio/20010schoolproj/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/emptyclass.PNG
    alt: "100% fre4e"
    title: "Other Side Projects"
    excerpt: ""
    url: "https://dattasiddhartha-3.github.io/portfolio/20015sideprojects/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 

  - image_path: https://raw.githubusercontent.com/dattasiddhartha-3/dattasiddhartha-3.github.io/master/images/opens.PNG
    alt: "100% fre4e"
    title: "Open-source Contributions"
    excerpt: ""
    url: "https://dattasiddhartha-3.github.io/portfolio/20020opensource/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 

---

### Siddhartha Datta

Thank you for venturing into my repository of project highlights, research experience, and looking glass into my personal life. While each page or section might go in-depth into a particular domain or problem or solution, the one thing that connects them all together is that each project I work on in some way *tests* the future of that domain, to test whether the solution is in this problem's path in the coming years/decades. 

<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>

<details>
  <summary>Click to expand!</summary>
  
  ## HCI / products (incl. CV, NLP, ML/DL)

  {% include feature_row %}

</details>

## HCI / products (incl. CV, NLP, ML/DL)

{% include feature_row %}

## Causal inference / inductive programming (incl. Bioinformatics, networks)

{% include feature_row2 %}

## Privacy preserving systems (incl. Obfuscation, adversarial attacks)

{% include feature_row3 %}

## Lab contributions

{% include feature_row4 %}

## Other contributions

{% include feature_row5 %}

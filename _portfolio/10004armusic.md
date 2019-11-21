---
title: "Music Generation through Food Detection, Assignment of Music Notes to Distinct Items, and Utensil Impact Detection"
excerpt: "An AR system where users put on a pair of goggles or a visualizer above highlights the food on the table, and users use their utensils to generate individualized music notes from tapping their food. "
collection: portfolio
---

[![IMAGE ALT TEXT](/images/armusic.png)](https://bit.ly/2UY9FM0)

An AR system where users put on a pair of goggles or a visualizer above highlights the food on the table, and users use their utensils to generate individualized music notes from tapping their food. 

[code](https://bit.ly/2P7YYRQ)

### Technical description

* Trained Resnet and Yolo object detection models on labelled food images; paired food categories with instruments, and sub-categories with different notes, and encoded x-axis location across the sub-category image with distinct notes

* Trained separate object detection model to identify utensils, and calculate proximity between utensils and food item (distance~0 infers impact)

* Human-computer interaction contribution in terms of augmenting a dining experience with sound, visuals and physical action.

### Motivation

This is an augmented reality system/game where people can see highlights (bounding boxes) over their food, and tapping their food will produce a certain instrumental sound to synthesize music (including guitar chords, piano on different scales, and drums); it executed on Mixed Reality lens with object detection

Download the repository and run the objectdetection+airdrums-ver2.ipynb notebook to run the model.

Sample videos: 

[Demo 1](https://bit.ly/2GcKUCl) | [Demo 2](https://bit.ly/2UY9FM0)

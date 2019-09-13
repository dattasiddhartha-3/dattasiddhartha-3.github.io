---
title: "Memory Palace: YOLO Object Detection to Locate Objects through Speech Recognition"
excerpt: "Winning submisson at Cal Hacks 5.0 (Epson sponsor award). Our team developed a pair of display goggles that helps patients with Alzheimer's or other visual/mental disabilities in locating their personal belongings. Users verbalize the item they are searching for (typically items from the COCO image dataset), and all objects detected would be highlighted."
collection: portfolio
---
[![IMAGE ALT TEXT](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/e253ebdepson_goggles_lq.PNG)]

This is what the user sees.

Over 24 hours our team built the embedded system that would permit Epson's Moverio goggles to detect specific objects for users. This included setting up voice recognition input for object commands, relaying the image from the goggles to a server PC, running an object detection system on the PC, and relaying the image in real-time back to the goggles. The object detection system was based on a Mask RCNN model trained on a modified image dataset. 

[![IMAGE ALT TEXT](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/ba06d3445330501_2205033879773905_1146807820524453888_n.jpg]

Completion of the object detection system backend: 
[![IMAGE ALT TEXT](images/moverioimage.png)]

Preview of my teammate testing the goggles out in real-time, while my PC displays what he is seeing:
[![IMAGE ALT TEXT](http://img.youtube.com/vi/s6UWctGQRwA/0.jpg)](http://www.youtube.com/watch?v=s6UWctGQRwA)










[code](https://hkustconnect-my.sharepoint.com/personal/sdatta_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley%2FMoverio%2DMemoryPalace%2DInstructions%2Ezip&parent=%2Fpersonal%2Fsdatta%5Fconnect%5Fust%5Fhk%2FDocuments%2FBerkeley)

[Installation instructions](https://drive.google.com/open?id=183nrhzzW63Xrgerxxk8LOU9aBcUO_XZH)

[Video demo](https://www.youtube.com/watch?v=s6UWctGQRwA&feature=youtu.be)

[Hackathon submission](https://calhacks5.hackerearth.com/sprints/cal-hacks-50/dashboard/b436967/submission/)

[slides](https://he-s3.s3.amazonaws.com/media/sprint/cal-hacks-50/team/475490/b524535calhacks_slides.pptx)

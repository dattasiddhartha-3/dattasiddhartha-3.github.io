---
title: "BreakupBot: An AI Therapeutic Chatbot Conducting Empathetic Counselling via Heartrate Sentimental Analysis"
excerpt: "BreakupBot is a therapeutic chatbot developed to help get over romantic breakups. Organically acquired 200+ users of varying demographics. The system, initially built to help people who could not get over breakups, uses scraped content from dating sites and builds a philosophical counselling knowledge graph as the decision tree for generating responses to user input."
collection: portfolio
---

BreakupBot is a therapeutic chatbot developed to help get over romantic breakups. Organically acquired 200+ users of varying demographics. The system, initially built to help people who could not get over breakups, uses scraped content from dating sites and builds a philosophical counselling knowledge graph as the decision tree for generating responses to user input.

<!-- [![IMAGE ALT TEXT](http://img.youtube.com/vi/1NxWMQA7tlM/0.jpg)](https://www.youtube.com/watch?v=1NxWMQA7tlM) -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/1NxWMQA7tlM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[[paper]](https://drive.google.com/file/d/142kTVrKNGH42splekvbfXGVtT9HhNQPq/view) [[code]](https://github.com/dattasiddhartha-4/breakup-bot/) [[app]](https://drive.google.com/open?id=1AVUpfepD_4yhdqv5L16C0XYDfLBk88om)

### Technical summary

* Built Android application and JSON-based API that receives user text input and returns counselling-based responses

* Based on real-time user variables (lover type, heartrate-sentiment approximation), categorized text corpus is filtered before running hidden markov chain text generator

* Used random forest classification model and hierarichal clustering to bucket users into John A. Lee’s six types of lovers based on preliminary text input

* Adopted script that estimates heartrate from camera image input based on measurement of signal peak difference at time intervals

* Scripted web scrapers to pull high-rated responses from love-related forums; constructed knowledge graph from corpora to facilitate filtering for text generator

### Motivation

The backstory of the project started off in my freshman year when my close friend got dumped by his girlfriend right before his final exams, and his GPA dropped from 3.7 to 2.7. It made me realize that even someone as intelligent as my friend could be vulnerable to the emotional dangers of romance. So I set out to figure out a way to help him recover. He did not want to talk about his situation with anyone and wanted to save "face", so I figured he could speak with a very smart bot.

I started out surveying the preferences of users (students who went through breakups recently), to validate the method of human-computer interaction, and to identify the optimal counselling approach. After settling on a chatbot interface, the next step was building the backend system. 

The first component of the system was user characterization (identifying which type of lover the user is based on discussion with the bot, based on the Love Attitudes Scale framework). The second component was heartrate sentitivity analysis to adjust the direction and sensitivity of responses generated. By using phone LED and camera to capture the redness of the finger and processing the image with Laure's algorithm, we can estimate heartrate as a proxy for instantaneous stress of the user mid-conversation. The third component would be usage of philosophical counselling (which is more open-ended and dialogue-based than psychological counselling). Based on Sternberg's Triangular Theory of Love, the bot would attempt to rationalize the relative position of the user in their relationship. The fourth component would be the source data of responses (scraped from dating sites or love advisory sites), and based on the personality adjustment mechanisms would run a text generation algorithm as response to user input. 

[![IMAGE ALT TEXT](/images/pipeline.PNG)](https://drive.google.com/file/d/142kTVrKNGH42splekvbfXGVtT9HhNQPq/view)

After building and testing the system within a group of test users, I additionally submitted the project to the [President's Cup](http://www.ust.hk/presidents_cup/). I was the only participant who was a Year 1 Business student and working solo; all other competitors are Post-graduate or Final Year students working in teams of four or five. 

[![IMAGE ALT TEXT](/images/poster.PNG)](https://drive.google.com/open?id=0Bya0t6OLDU2FNTV2S2NKTmpMSHc)

<img src="/images/bb1.png" width="180"> <img src="/images/Inkedbb2_LI.jpg" width="360">

[prototype](https://www.facebook.com/BreakupBot-20-1328526643902687/) | [video](https://www.youtube.com/watch?v=1NxWMQA7tlM) | [poster](https://drive.google.com/open?id=0Bya0t6OLDU2FNTV2S2NKTmpMSHc) | [Further reference and media](https://drive.google.com/open?id=0Bya0t6OLDU2FZFk1UzdiMU5qb1U)

You may install the [apk file](https://drive.google.com/open?id=1AVUpfepD_4yhdqv5L16C0XYDfLBk88om) for Android. You may also preview a simplified demo of the NLP system through [Facebook](https://www.facebook.com/BreakupBot-20-1328526643902687/): Click "Send Message" to start interacting with the isolated NLP system.

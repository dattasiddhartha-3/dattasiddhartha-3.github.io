---
layout: archive
title: ""
permalink: /publications/
author_profile: false
---

### Resume

<iframe src="https://drive.google.com/file/d/1ft6yD26gz87DvQJsdwMPuRzV4gIIFclB/preview" width="640" height="480"></iframe>

### Formal paper submissions

##### S. Datta. 2019. Submitted. ["DeepObfusCode: Source Code Obfuscation Through Sequence-to-Sequence Networks"](https://arxiv.org/abs/1909.01837) In ICASSP 2020
The paper explores a novel methodology in source code obfuscation through the application of text-based recurrent neural network (RNN) encoder-decoder models in ciphertext generation and key generation. Sequence-to-sequence models are incorporated into the model architecture to generate obfuscated code, generate the deobfuscation key, and live execution. Quantitative benchmark comparison to existing obfuscation methods indicate significant improvement in stealth and execution cost for the proposed solution, and experiments regarding the model's properties yield positive results regarding its character variation, dissimilarity to the original codebase, and consistent length of obfuscated code.

##### S. Datta, C.Z Koval. 2018. ["Big Data Analysis of Labour Market Dynamics in Freelance Work Platforms"](https://drive.google.com/open?id=1nOAZuAtAsVhJHUXCp3Re_1LSnE9LOerZ) In [Undergraduates Research Opportunities Program 2017-2018 Proceedings](https://urop.ust.hk/files/UROP%20Proceedings%202017-18.pdf)
This research aims to explore the underlying relational dynamics between people on freelance work platforms, between employers and employees, and within employees themselves. Particular interest will be placed on gender correlations and the objective to locate the most important variables involved in reasonable pay, as the aim of the study is to identify biases on the platform. Data was scraped from the work platform for all the possible variables available, from tests taken, to work histories, to skills listed, to even general personal descriptions.

##### S. Datta 2018. ["HAIV: Computational Precision Medicine against HIV Drug Resistance"](https://drive.google.com/open?id=1UwI3d3BeTJiHmEiT8r4QizsMBvl6ONaI) In HKNGCA Challenge Cup (Finalist)
This paper introduces a novel methodology to treat HIV through the combination of existing antiretroviral therapy with mutation prediction algorithm (“HAIV”). The algorithm developed predicts the next possible mutations that a given HIV strain may undergo, and implies doctors can apply the right medication at the right time, hence alleviating the need to apply more variations of medication
than needed, further suppressing the possibility for drug resistance. The work is deemed to be novel and without any prior work in the industry thus far, and the applications range from any task requiring the prediction of mutations, or any virus dealing with drug resistance.

##### S. Datta, S.L. Nam 2017. ["BreakupBot: An Artificial Intelligence Therapeutic Chatbot Conducting Empathetic Counselling via Heartrate Sentimental Analysis"](https://drive.google.com/open?id=142kTVrKNGH42splekvbfXGVtT9HhNQPq) In President's Cup 2016-17 (Finalist)
BreakupBot is the title of a chatbot platform that aids people to recover from their romantic breakups. To cater to a heterogeneous audience, there will be several therapy mechanisms in place to ensure every type of lover will be catered to. Some users may wish to think deeply about relationships, while some may need to gain maturity about love in general; in either case, the AI behind the chatbot will personalize itself to the user, and adopt both psychological and philosophical counselling methodologies. Personalization ranges from understanding the user’s lover characteristics, analyzing the user’s stress levels via heartrate, and responding instantaneously to their every query and woe. The technology is adept and fitting for complementing the bot: other than the artificial intelligence system that collects information to share with the user and personalizes it to the user’s taste, the bot features accurate heartrate analysis
available to most smartphones via camera-detection. Such a mechanism will aid the bot in empathizing with the user, contrary to other bots who attempt facial recognition or process speech patterns. Moreover, this project merely represents the beginning of further exploration into psychological therapeutic benefits via AI. Once the BreakupBot penetrates the market wide enough to allow entry to other similar products, other therapeutic bots and mechanisms can be designed to streamline human being’s complicated lives and emotions. This project is a goldmine, with respect to the fact that it creates its own category of products: it is not in the personal assistant AI category, but the currently underdeveloped therapy AI category, hence there is a lot of potential for research and profit. At the end of the day, the value of this project is not only its intrinsic research, or its mechanisms, or its cross-departmental field of study; its value comes from robots attempting to solve the problems of human beings at a psychological level.

##### A. Goel, K. Slama, S. Datta, L. Dong. 2018. "Predicting Value-based Decision-making using Time Series neural ECoG data" In Data-X 2018 [code](https://github.com/dattasiddhartha/DataX-NeuralDecisionMaking) [poster](https://data-x.blog/projects/predicting-gambling-decisions/) [data](https://crcns.org/data-sets/ofc/ofc-3/about-ofc-2) [library](https://github.com/dattasiddhartha/neurocogpy)
A project focused on predicting gambling decisions from brainwave electrocorticography (ECoG) data. The motivation behind this project was based on societal implications such as applications to law and regulation of the gambling industry, clinical practice in understanding how neurodegenerative disease or trauma affect decision making, and to some extent even our understanding of free will. The project utilized data recorded by the Knight Lab, a neuroscience lab at UC Berkeley. The ECoG data was collected from the orbitofrontal cortex (OFC) of epileptic patients, who volunteered to participate in research while undergoing intracranial monitoring for surgical planning purposes. Patients were given a task of playing a game in which they could choose either ‘Gamble’ or ‘Safebet’ for 200 trials. Over the course of the semester, we pre-processed, explored, and modeled the data, with the ultimate goal of predicting whether a patient would gamble or not given only the ECoG data, recorded before the patient indicated their decision by a button press. Much exploration was on feature engineering, as there are not many established feature engineering methods in the analysis of ECoG data: examples of features include using the 2.5 and 97.5 percentile values and number of peaks for electrode data in a patient’s trial. Modeling was done through logistic regression, random forest, adaboost, naive bayes, neural nets, and perceptron. Logistic regression fared the best, with one model giving a 10% boost over the baseline accuracy found with Naive Bayes. This result demonstrates that there is information in the OFC neural signal, which can be used to predict decisions before they are made overtly.

### Research contributions

###### [o] open-source; [c] closed-source

##### [Polysemy Word Tagging Tool](https://github.com/dattasiddhartha/polysemous-word-tagging-tool) [o]
Worked under supervision of **Prof. Mahesh Srinivasan** of **Language & Children Development Lab (UC Berkeley)**

Built polysemy word tagging tool for the LCD lab to help in tagging words for multiple meanings and facilitate pattern detection

##### CalUnmanned
* Worked with team of engineers under supervision of **Prof. Raja Sengupta** to develop autonomous drone system for crack detection
* Developed Unity-based system for training drone flight through reinforcement learning

##### Credit Suisse (Advanced Execution Services) [c]
* Developed new market impact models based on foundations of the Algrem-Chriss model, including limit order book based price prediction models, ensembling models based on TCA data
* Constructed hidden cross-trade opportunity detection system. Problem: Salestrader need to identify potential cross-trade opportunities between clients. Solution: my model took client’s historical flows, trade execution patterns, holdings, and patterns of similarity between clients and stocks, and generated a daily list of clients who would likely be trading a certain stock. Built trade flow prediction model, predicting client flow at hourly intervals in specific stocks; built network model between clients and stocks that used reinforcement learning to calculate weights on the different variables that create affinity of clients to certain stocks; Cleaned and integrated resources from all over the bank, ranging from equity research’s readership data, to securities lending’s locates data, to trade execution data from high and low touch, to even indication of interest (IOI) data. Backtested to work >60% prediction accuracy in overlap between clients predicted to trade on a certain day on specific stock.

##### Hong Kong University of Science and Technology
* Worked under **Prof Yang Yi** on: (i) adversarial attacks on sentiment classification models; (ii) grammar error correction models focused on cross-language errors
* Worked under **Prof Christy Zhou Koval** on analysis of gender and race bias on online work platforms: Built a web-scraper, and built an workaround to bypass CAPTCHA security mechanisms; managed room of 11 computing resources simutaneously; Analyzed data, plotted and studied social network interaction charts and relations within employees and employers

##### [_neurocogpy_](https://github.com/dattasiddhartha/neurocogpy) [o]
* Neuroscience visualization library built in affiliation with Data-X and Knight Lab (UC Berkeley).

### Additional research work

##### ["Using Structural Imbalance to Evaluate Models of International Relations"](https://drive.google.com/open?id=1lUfM2D4XycYqbIgJThU1Xjk0sdku4z3n)

##### ["Power and Politics in Academia: A Network Analysis"](https://drive.google.com/open?id=1QeZQ_kntH01j5cPpZE9vsg7nKkvfWzk5)

##### ["Location Network Fingerprinting"](https://drive.google.com/open?id=1aOQiZsVpe2V5yjKr-_aAqeqCny1E2izo)

##### ["Youtube Sentiment-based Portfolio Selection and Trading Strategy"](https://github.com/dattasiddhartha/QuantTrading_Decal)

##### ["AIDS Epidemic Simulation with Adjustment for Decision-making from neural ECoG data"](https://drive.google.com/open?id=17WZ1hRXWdA-ppuXmkyBdVcu26os3wALx)

### Scholarships/Honors:
+ Dean's List (2017-18, 2018-19)
+ Joseph Lau Luen Hung Charitable Trust Scholarship Hong Kong Award (HK$ 80,000 p.a.)
+ Li Ka Shing Foundation Scholarship for Innovation and Creativity (HK$ 50,000)
+ Hong Kong Unison Scholarship (HK$ 15,000 p.a.)
+ Br Bernard Guellec Memorial Prize for French
+ Br Felix Sheehan Memorial Prize for English
+ University Entrance Scholarship
+ Harmony Scholarship (Home Affairs Bureau, HKSAR Government)

_* Total scholarship HK$ 110,000 per year; 2.5x annual tuition

_** Awarded to Top 0.0015% of undergraduate student population


### Awards:
*2018*
+ CalHacks 5.0 - Winner (Augmented Reality section, Epson Sponsor Award)
+ SacHacks 2018 - Winner (Smartcar 1st Runnerup, Best First-Time Hack, Best Domain Name, 3rd Overall)
+ AngelHack 2018 - Champion (Blockchain Category)
+ Classified Post Hackathon 2018 - Champion
+ Access to Justice InnoTech Law Hackathon 2018 - Honorable Mentions
+ CityU Hackathon 2018 - Most Innovative Idea & 1st Runnerup

*2017*
+ HKUST-Radica Big Datathon 2017 - 2nd
+ Cyberport Creative Micro Fund - Winner
+ EasyShip 24 Hour E-Commerce Hackathon 2017 - 1st Runner up
+ Hack the Runway 2017 - Champion
+ HardUST 2017 - 1st Runner-up


### References:
* Prof Eric Friedman, EECS, UC Berkeley
* Prof Christy Zhou Koval, Michigan State University
* Prof Gary Chan, Computer Science, HKUST
* Prof Yang Yi, Information Systems, HKUST
* Dr Nora Hussein, Linguistics, HKUST
* Dr Nam Sai Lok, Philosophy, HKUST
* Peers testimony: [CalHacks](http://www.zacharychaoportfolio.com/blog/calhacks), [SacHacks](http://www.zacharychaoportfolio.com/blog/sacHacks)
<!-- * Prof Thomas Bourveau, Accounting, Columbia University -->
<!-- * Prof Ikhlaq Sidhu, Industrial Engineering & Operations Research, UC Berkeley -->
<!-- * Prof Ted Clark, Information Systems, HKUST -->

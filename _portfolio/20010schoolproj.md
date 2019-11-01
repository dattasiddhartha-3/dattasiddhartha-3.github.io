---
title: "Past School Projects"
excerpt: ""
collection: portfolio
---

### "Worst Movie Ever" - Data Visualizations project

[![IMAGE ALT TEXT](/images/school1.PNG)]

This is a project for INFO190 at UC Berkeley, where my team used Illustrator, Tableau and d3.js to build this website that identifies the perfect combination of variables to make the worst movie.

[Website](https://worstmovieever.weebly.com/)

[d3.js code](https://github.com/dattasiddhartha/INFO190-DATAVIZ)

Sample visualization:
<iframe width="1000" height="300" src="http://dattasiddhartha.github.io/INFO190-DATAVIZ"></iframe>


### Audio Style Transfer

[![IMAGE ALT TEXT](/images/school2.PNG)]

A cybersecurity course where we dedicated our final project to replicating the course professor's voice. (ISOM4200 HKUST)

[Repo](https://github.com/dattasiddhartha/audio-style-transfer)

### Predicting Value-based Decision-making using Time Series neural ECoG data

[![IMAGE ALT TEXT](https://i1.wp.com/data-x.blog/wp-content/uploads/2018/12/Brain-Poster-Aditya-Goel-page-001.jpg?zoom=2&resize=2000%2C1200&ssl=1)]

On Tuesday December 4, a group from SCET’s Data-X class presented on a project focused on predicting gambling decisions from brainwave electrocorticography (ECoG) data. The motivation behind this project was based on societal implications such as applications to law and regulation of the gambling industry, clinical practice in understanding how neurodegenerative disease or trauma affect decision making, and to some extent even our understanding of free will. The project utilized publicly available data recorded by the Knight Lab, a neuroscience lab at UC Berkeley. The ECoG data was collected from the orbitofrontal cortex (OFC) of epileptic patients, who volunteered to participate in research while undergoing intracranial monitoring for surgical planning purposes.

Patients were given a task of playing a game in which they could choose either ‘Gamble’ or ‘Safebet’ for 200 trials. Over the course of the semester, the Data-X group pre-processed, explored, and modeled the data, with the ultimate goal of predicting whether a patient would gamble or not given only the ECoG data, recorded before the patient indicated their decision by a button press. Much exploration was on feature engineering, as there are not many established feature engineering methods in the analysis of ECoG data: examples of features include using the 2.5 and 97.5 percentile values and number of peaks for electrode data in a patient’s trial. Modeling was done through logistic regression, random forest, adaboost, naive bayes, neural nets, and perceptron. Logistic regression fared the best, with one model giving a 10% boost over the baseline accuracy found with Naive Bayes. This result demonstrates that there is information in the OFC neural signal, which can be used to predict decisions before they are made overtly.

[code](https://github.com/dattasiddhartha/DataX-NeuralDecisionMaking)

[poster](https://data-x.blog/projects/predicting-gambling-decisions/)

[data](https://crcns.org/data-sets/ofc/ofc-3/about-ofc-2)

_Reference:_

_Ignacio Saez, Jack Lin, Arjen Stolk, Edward Chang, Josef Parvizi, Gerwin Schalk, Robert T. Knight, Ming Hsu. Encoding of Multiple Reward-Related Computations in Transient and Sustained High-Frequency Activity in Human OFC. Current Biology, Volume 28, Issue 18, 24 September 2018, pages 2889-2899.e3_

### Stock Analzer

VBA-coded user interface to analyze stocks, for ISOM3230 (HKUST).

[code](https://github.com/dattasiddhartha/StockAnalyzerGUI)

### 2048 AI-version

The standard 2048 game mechanism with an overlay of different settings and an expectimax-based solver as an add-on. For ISOM3230 (HKUST)

[code](https://github.com/dattasiddhartha/2048_AI)

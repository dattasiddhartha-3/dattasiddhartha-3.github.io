---
title: "Location Network Fingerprinting: Network Analysis of Franchise Expansion"
excerpt: "After aggregating expansion data from sucessful franchises/chains from many industries (including fast food, supermarkets, coffee, ...), we developed network analysis algorithms that identified statistically-likely patterns or fingerprints of expansion success. Specifically, we found that certain succesful firms tended to expand in certain ways that consolidated their success. We found the results to be 98% statistically significant, and pitched the system as a service for firms intending to expand within the US but are strategically unsure how."
collection: portfolio
---

After aggregating expansion data from sucessful franchises/chains from many industries (including fast food, supermarkets, coffee, ...), we developed network analysis algorithms that identified statistically-likely patterns or fingerprints of expansion success. Specifically, we found that certain succesful firms tended to expand in certain ways that consolidated their success. We found the results to be 98% statistically significant, and pitched the system as a service for firms intending to expand within the US but are strategically unsure how.

[code](https://github.com/dattasiddhartha-1/Berkeley-Demand-Enterprises)

### Motivation

[![IMAGE ALT TEXT](/images/fingerprint.PNG)]

The image shows two common patterns of expansion by successful firms. Firms that tend to start out in Utah, Colorado, Phoenix or New Mexico tend to expand across the four corners of the square before expanding to other parts of the US. Successful coffee chains that start out in Seattle tend to branch out to Alaska as a first step. The latter did not make much sense to me initially, until I found out Alaskans are the largest consumers of coffee in the US. This indicated there is insight to be discovered in these expansion patterns.

The idea sparked after reading [Wherefore art thou R3579X?](https://personal.utdallas.edu/~mxk055100/courses/privacy08f_files/social-network-privacy-backstrom.pdf), a paper that described the process of user deanonymization based on their social network patterns. Even after anonymizing the names of the users, based on who they are connected to in a social network, you could identify users, and I saw the parallel to firm expansion. I gathered a dataset of firms and all their present locations. The timestamps for when each store was launched was not available, but based on the success of each firms that we could cluster, we were able to identify consistent patterns of expansion. Below is an example of one of our "fingerprinting" algorithms identifying the most common expansion coordinates, and other implemented algorithms were based on bridge detection in network graphs.

[![IMAGE ALT TEXT](/images/fingerprint2.PNG)]

You may consider going through the graphs in the slide deck for a better understanding of the implementation, and additional patterns we found.  

<iframe src="https://drive.google.com/file/d/1aOQiZsVpe2V5yjKr-_aAqeqCny1E2izo/preview" width="640" height="480"></iframe>

### Technical summary

* Hybrid implementation of motif-detection, bridge-detection, and clustering algorithms to yield sequential coordinates of geographical locations depending on category of product/business, based on network de-anonymization framework

* Developed REST API to run algorithm and pass JSON-formatted output to Ruby on Rails frontend

* Contributions of this work in the use of network graphs in time-independent pattern interpolation, recursive backtesting method of running/validating the motifs through training/testing franchises

[implementation details](https://drive.google.com/open?id=1aOQiZsVpe2V5yjKr-_aAqeqCny1E2izo) | [algorithm](https://github.com/dattasiddhartha/Location-Network-Fingerprinting)

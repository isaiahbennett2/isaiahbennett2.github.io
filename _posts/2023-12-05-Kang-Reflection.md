---
title: "Reflection of Kang et al. 2020 Reanalysis"
excerpt_separator: "<!--more-->"
categories:
  - Reproduction
tags: 
  - Reproduction Study 
  - COVID-19
  - Network Analysis
---

[Link to the reanalysis](https://isaiahbennett2.github.io/RPr-Kang-2020//)

[Link to the original study](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x)

This was not only the most collaborative, but also the most advanced reproduction study that I have done so far. Kang et al. is a network analysis study that looks at the accessibility of COVID-19 healthcare resources such as hospital beds and ventilators to at risk populations (over 50 years old) and covid cases over the state of Illinois based on road networks and speed limits. Due to incredibly large file sizes the reproduction focuses solely on the city of Chicago Expanding off the [previous work](https://github.com/isaiahbennett2/RPr-Kang-2020/blob/main/procedure/code/02-COVID-19Acc-Original.ipynb) of the class, this renalysis improved the study by implmenting two major changes: 
1. Replacement of incorrect data values for road speed limits with new inferred speed limit values from OSMNX road types
2. Implementation of Area Weighted Aggregation to aggregate data into hexagonal grid instead of using the original 50% threshold method 

First, we delved into the realm of CyberGIS by learning how to connect to the cybergisx environment created by the University of Illinois at Urbana-Champaign that hosts their super computers to run this computationally intensive study on. 

Next, together as a class, we indentified a multitude of possibilities for how we could improve the study after a critical reading and discussion of its contents. We landed on the above two implementations because of their tangibility for the scope of our class and their possibility of their producing interesting results. While I worked mostly on the AWR, the main work on the OSMNX speed limit values was executed by Elise Chan and Alana Lutz. After finishing the code for these specific implementations, code was shared and discussed with the whole class so that we could each write our own discussions and conclusions to the study. 

Overall, this reproduction study was incredibly valuable in how it modeled more advanced components of open, reproducible research such as more group collaboration, data sharing, and cyber GIS, as well as posed the most difficult coding challenges yet. 
Ultimately, our changes were successful at addressing threats to validity by reducing data generalizations and eliminating aggregation uncertainties. To go beyond our reanalysis, the next steps for improving this study would be to address space-time threats to validity such as the studies limited scope of only a personal vehicle transportation network by adding multi-modal transportation networks, and implementing time of day traffic congestion data to more accurately assess when cars are able to drive the speed limit. Furthermore future work could address the potential partition-distortion threat to validity of the size of the hexagonal grid to see whether it influences the representation of true accessibility. 

Enjoy!

[Link to research compendium for this reproduction study](https://github.com/isaiahbennett2/RPr-Kang-2020)

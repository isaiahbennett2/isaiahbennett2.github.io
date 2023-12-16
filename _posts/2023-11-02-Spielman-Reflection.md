---
title: "Reflection of Spielman et al. 2020 Reproduction"
excerpt_separator: "<!--more-->"
categories:
  - Reproduction
tags: 
  - Reproduction Study
  - Social Vulnerability
  - SoVI Model
---

[Link to the reproduction study](https://isaiahbennett2.github.io/RPl-Spielman-2020/)

Reproduction #3!
This reproduction was a little different than the last two since it was a reproduction of Spielman et al.'s 2020 ["Evaluating social vulnerability indicators: criteria and their application to the Social Vulnerability Index"]( https://doi.org/10.1007/s11069-019-03820-z) which is a reproduction of Cutter et al.'s 2003 ["Social vulnerability to environmental hazards"](https://doi.org/10.1111/1540-6237.8402002). The Cutter et al. 2003 piece has been incredibly influential in the field with over 7000 citations. Her study essentially laid the foundation for how to create a social vulnerability model setting an example for geographers and policy makers alike. Although her model has been used a lot, there is a great lack of external validation which is especially important since the assessment of the social vulnerability of an area can directly influence how resources and support are distributed to such an area in response to a disaster. Spielman et al. 2020 serves to externally validate her popular study and our reproduction of Spielman et al. 2020 improves upon their work.

This was the second version of our reproduction of the Spielman study, so to improve on our previous work I first implemented a couple new visualizations such as a Map of SoVI scores of every county in the entire US, along with a data table of the National SoVI loadings from the Principal Component Analysis. To expand on the original Spielman reproduction more, I also calculated the percent variance explained by each variable in the loadings which I then used to weight the National SoVI score to investigate if weighting the variables by the proportional variance explained would have any effect on the final scores and rankings. A simple Spearmans R correlation test demonstrated that there was no significant impact of the weighting on final scores. While these results were underwhelming, they showed me the importance of investigating a possible area of uncertainty in the construct validity of such an influential study even if that specific aspect of the study did, in fact, have a strong theoretical consistency. 

Not only did this reproduction present new learning opportunities through adapting to the new spatial Python environment that it was conducted in. This process of identifying areas of potential uncertainty in research design showed me what true external validation can look like. 

Check it out to see these results added to our newest version of our reproduction of Spielman et al.!



[Link to research compendium for this reproduction study](https://github.com/isaiahbennett2/RPl-Spielman-2020)

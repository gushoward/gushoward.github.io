---
title: "Chakraborty (2021) Reproduction"
categories:
  - Blog
tags:
  - Reproducibility
  - MAUP
  - COVID-19
---

Our most recent project in OpenGIScience was an attempt to reproduce Chakraborty’s 2021 study ‘Social inequities in the distribution of COVID-19: An intra-categorical analysis of people with disabilities in the U.S.’ The study, and my subsequent reproduction, applies statistical analysis techniques - such as bivariate correlations and generalized estimating equations to understand the relationship between COVID-19 cases and people with disabilities. Unfortunately, the reproduction of the study was diverted as a result of some differences in the data, meaning my analysis only went so far as to compare SaTScan clusters to SpatialEpi clusters, thus not including the entire GEE modeling that the authors undertook. Using the Kulldorf and the clustering methods were novel to me but yielded interesting comparisons. The results might suggest that people with disabilities face disadvantages resulting from various factors, including their disability, and COVID-19, although further studies are required to make more definitive conclusions in this regard. 

Kedron and Holler (2024) emphasize the importance of paying careful attention to how geographic concepts are operationalized, as spatial studies risk drawing misleading or overly generalized conclusions. In turn, policy decisions could be made based on the back of incomplete or misleading research. Chakraborty (2021) suffers some common pitfalls of geographic research such as the modifiable areal unit problem (MAUP) which in this case treats counties with widely varying population sizes with equal analytical weight. Ideally the scale of analysis would be at the individual level which is of course impossible, but county-level assumptions may be misleading. This is especially true when much of the data has high margins of error. It is important to consider these issues before drawing serious conclusions and implementing these into policy and management decisions.

I quite enjoyed the reproduction and reanalysis of the study, as I was introduced to new methods and ways to analyze a phenomenon (COVID-19) that I have applied geographic analysis techniques to before.

## References

Kedron, P. and Holler, J. (2024). Validation and Verification of Applied GIS Research. The Geographic Information Science & Technology Body of Knowledge (2024 Edition), John P. Wilson (ed.). DOI: 10.22224/gistbok/2024.1.13
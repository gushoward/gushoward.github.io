---
title: "Final Reproduction - Blog Post"
last_modified_at: 2025-05-09T16:20:02-05:00
categories:
  - Blog
tags:
  - Reproducibility
  - Replicability
  - Crime
---

Whilst replicating this study, we came across a number of deviations that we had to make, as well as some limitations and issues with the original study. One limitation in the conceptualization of this study lies in its reliance on predefined administrative boundaries, such as county subdivisions, which may not accurately reflect the social and environmental contexts influencing crime. This approach can lead to the Modifiable Areal Unit Problem (MAUP), where statistical results vary based on the spatial units used, potentially obscuring localized crime patterns and leading to ecological fallacies when inferring individual behaviors from aggregate data. 

The study’s use of the Shannon Index - an ecological species diversity measure - as a use for human diversity and how this impacts crime rates is especially problematic and misleading. When using the Shannon Index, diversity levels are considered as the level of evenness across eight racial groups, which does not represent true diversity, especially when analyzing a smaller geographic area such as Connecticut. Also, the assumptions made on the back of the Shannon index numbers are troubling. The study writes: “racial/ethnic heterogeneity weakens residents’ attachment to the areas where they live and reduces community organization and involvement” (Meng 2021). The implication that community engagement is greater in less diverse communities is based on falsehoods that instead come from a variety of factors, not race (Portes 2015). Additionally, the study's focus on certain socioeconomic variables may overlook other influential factors like cultural dynamics, community cohesion, or informal social controls that are harder to quantify but significantly impact crime rates. 

Regarding the measurement of crime, the UCR crime data is reported by county subdivision which may result in variations in law enforcement practices, reporting standards, and resource allocation across these jurisdictions. The result may be inconsistencies in crime data, complicating comparisons and trend analyses. Studies like this can influence policy decisions, potentially amplifying the effect of these inconsistencies. 

ACS has large margins of error for each statistic so when dealing with smaller, less populous geographic areas like Connecticut, these margins are often quite high. When these data are used as predictors in regression models or spatial analyses, the underlying uncertainty can lead to unstable or misleading results. This is part of a larger problem that we faced in our replication study, which is the original study’s lack of clarity regarding their choices in variables, models, and more. We have experienced a significant number of deviations in the data - and although they may be minor, these differences compound to create large gaps in the models and our ability to replicate the original study’s models. 

The author importantly notes that discussions of crime should be more locally focused and context specific. Policy and policing of crime should reflect this context and the natural spatial variation of all forms of crime. The data and models used in the study show that there is spatial variation in the data but the models have little to no predictive power thus conclusions regarding the effect of diversity on crime and social capital, for example, should not be given too much weight. Further work and analysis needs to be done beyond the geographic weighted regression to apply conclusions to these relationships.



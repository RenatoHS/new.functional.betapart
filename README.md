new.functional.betapart

A faster version of the functional.betapart.core from the "betapart" package in R. The function is used to decompose the functional beta-diversity of communities into the turnover and nestedness components, and it is an extension of the original method that was designed for the taxonomic perspective. 

Refer to the following references for the betapart package

Baselga, A. (2010). Partitioning the turnover and nestedness components of beta diversity. Global Ecology and Biogeography, 19(1): 134-143.

Baselga, A. and C. D. L Orme (2012). betapart: an R package for the study of beta diversity. Methods in Ecology and Evolution, 3(5): 808-812.

Villéger, S., Grenouillet, G. and S. Brosse (2013). Decomposing the functional B-diversity reveals that low functional B-diversity is driven by low functional turnover in European fish assemblages. Global Ecology and Biogeography, 22: 671-681. 


This new version allows for external parallelization and is substantially faster than the original one when dealing with # large community matrices.


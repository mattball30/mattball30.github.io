---
title: 'Introducing reaction condition prediction'
date: 2024-08-14
permalink: /posts/2024-08-14-Introducing-reaction-condition-prediction/
toc: true
tags:
  - PhD
---
As mentioned in my [bio](/_pages/about.md), my PhD is centred around a project titled: ‘Prediction of optimal reaction conditions using Artificial Intelligence tools’, but what are ‘optimal reaction conditions’? Reaction conditions are the environmental conditions that a (chemical) reaction proceeds under. For completeness, a chemical reaction is a transformation from one (or more) chemical species to one (or more) chemical species. Examples of reactions are given below: 

![Demonstration of different selectivities with different conditions](/images/Blog%20Figures.pdf)

# Why are chemical reaction conditions important? 
So why are the conditions important? Unfortunately, in the vast majority of cases, we cannot just mix the building blocks of our desired product together and get said product. Specific reaction conditions are required to get the reaction to:
- actually happen
- happen with the correct regioselectivity (i.e. reaction happens on the correct location of the species of interest, so that the correct regio-isomer is produced) ^8ab875
- happen with the correct stereoselectivity (ensures the molecule has the correct 3D structure which can be important when synthesising drugs)

IMAGE HERE 

Beyond simply getting the desired product, changing the conditions can change the yield (how much product we produce) which is important when considering the economic viability of a reaction. There should also be cost and environmental considerations with the conditions we select (avoiding expensive transition metal catalysts, environmentally unfriendly solvents etc.). The point concerning yield is particularly important when considering the synthesis of a pharmaceutically-relevant product, where the reaction product might need to be used for the next stage of a synthesis. Producing an insufficient amount of this ’intermediate’ means that the synthesis cannot continue and the resources used up to this point have been wasted. 

Issues of selectivity (see above), as well as side reactions and degradation of reactants/products all lead to lower yields and must be considered when designing syntheses.

All of these factors combine to make reaction condition prediction a complex, interdependent optimisation task, as changing one condition may alter the impact of another. 


# References

[^1]: Chen L-Y, Li Y-P. Machine Learning-Guided Strategies for Reaction Condition Design and Optimization. ChemRxiv. 2024; doi:10.26434/chemrxiv-2024-wt75q This content is a preprint and has not been peer-reviewed. 
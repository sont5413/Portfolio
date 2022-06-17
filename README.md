# Willis Sontheimer Portfolio

## [Project 1: Factors Influencing Antler Size in Mature (4.5 & 5.5 years) Male White-tailed-Deer](https://github.com/sont5413/Predictors-of-Antler-Size-in-Mature-4.5-5.5-White-tailed-Deer)
### I wanted to see what features influence antler size of mature (4.5- and 5.5-year-old) male white-tailed deer.
* Data: This is a unique dataset from a captive colony of white-tailed deer with known age, antler mass (kg), and maternal / paternal parentage.
* Each male was fed ab libitum one of two kinds of pelleted feed that differed in digestible energy, but had similar protein percentage (16%) from the time they were weaned. The standard energy diet 'S' had 2.65 kcal/g of dietary energy and the low energy diet 'L' had 1.77 kcal/g of dietary energy.

## Findings
* DaB and Lit Type were not important feature. Therefore, their output will be ignored in favor of the larger dataset where they were not included as predictors. 

### A. 4.5-year-olds:

#### Antler size of 4.5-year-old males is most influenced by the birth weight of the male. What's most surprising here is that, when it comes to determing antler size of mature males, it didn't really matter whether males had been eating a low or high energy diet ('Energy') throughout their life

![image](https://user-images.githubusercontent.com/95881308/174356911-32e0dcf2-3de1-4c5f-97c4-1eacf9ea46f6.png)

### B. 5.5-year-olds: 

#### Like in 4.5-year-olds, antler size of 5.5-year-old males is most influenced by the birth weight of the male. The father of the individual male ('SID') was the second highest ranked feature. Also, eating a low or high energy diet ('Energy') was not an important feature in predicting antler size of 5.5-year-olds.

![image](https://user-images.githubusercontent.com/95881308/174356922-f911d2bd-3fa6-4241-b419-e0aa2b9bc340.png)


## [Project 2: Predicting Winners of UFC Fights](https://github.com/sont5413/UFC-Fight-Data)
I built 3 models to predict the winner of a UFC fight based on age, height, and so on of the "red" fighter and the "blue" fighter.
* Random Forest 
* Linear Regression
* Gradient Boosting
### The Random Forest Classifier model had the least mean absolute error and differed from the observed winner about 40% of the time.  In other words, it predicted the correct winner about 60% of the time!

### As shown by the figure below, clearly no feature alone has huge explanatory power. In fact, most have very little explanatory power (roughly ≤ 0.03). However, the number of UFC fights a fighter had previously "BPrev" had the most predictor power.
![image](https://user-images.githubusercontent.com/95881308/172012522-218d8f87-146d-469a-b100-7e3e42fb171f.png)


## [Project 3: Analyzed Factors Influencing Body and Antler Size Relationships in White-tailed Deer: Project Overview](https://github.com/sont5413/Deer-scaling-relationships)
* Analyzed the degree to which maternal attributes (i.e., litter type and mother's age) and dietary energy influence body:antler size scaling relationships in white-tailed deer.
* Analyzed these relationships at two levels: 1) through the entire lifespan of individuals, and 2) at 5 different age groups (i.e., 1.5, 2.5, 3.5, 4.5, and 5.5).
* antler size and body size were log transformed in the .csv


#### Figure 1. Predicted regressions summarizing relationships between body mass and antler mass for male white-tailed deer fed either a low energy diet (L) or standard energy diet (S) in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654752-fd61734b-f805-4ac9-9022-4ad25e9c69da.png)


#### Figure 2. Predicted regression lines depicting the relationship between body mass and antler mass for male white-tailed deer aged 1.5 years fed either a low energy diet (L) or standard energy diet (S) and born to either a multiples or singleton litter in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654947-df38b97f-eae9-449f-9668-426da6bee2ed.png)



## [Project 4: Analyzed COVID-19 case rates for the month of January 2021 across 5 states that showed the highest increase in new cases](https://github.com/sont5413/CovidCasesJAN21)
* I analyzed an intercepts and slopes linear mixed effect model with State as the random factor.
* I also analyzed the 95% confidence interval of the fixed effect slope to conclude if rates vary among states. 
* My results show that the rate of exponential growth does not vary across the states. 
* The slope estimate for all five states (5.02) has a tight 95% confidence interval (4.28 to 5.75) that does not overlap zero (See Table 2, “Fixed Effects”).  
* Trellis plots of the data also show similar rates across all five states (See ancillary reporting on the last page of this report).
* I estimated a single model instead of a model for all 5 states in order to decrease the probability of committing a Type I error.

![image](https://user-images.githubusercontent.com/95881308/150697008-2fa3e27e-3c78-405d-b9a2-dc4bfdb85ea2.png)



# Willis Sontheimer Portfolio

## [Project 1: Factors Influencing Antler Size in Mature (4.5 & 5.5 years) Male White-tailed-Deer](https://github.com/sont5413/Predictors-of-Antler-Size-in-Mature-4.5-5.5-White-tailed-Deer)
### I analyzed features that were assumed to influence antler size of mature (4.5- and 5.5-year-old) male white-tailed deer.
* Data: This was a unique dataset from a captive colony of white-tailed deer with known age, antler mass (kg), and maternal / paternal parentage.
* Each male was fed ab libitum one of two kinds of pelleted feed that differed in digestible energy, but had similar protein percentage (16%) from the time they were weaned. The standard energy diet 'S' had 2.65 kcal/g of dietary energy and the low energy diet 'L' had 1.77 kcal/g of dietary energy.

## Findings
* DaB and Lit Type were not important features. Therefore, the two smaller datasets that included them were not interpreted.

### A. 4.5-year-olds:
* Antler size of 4.5-year-old males was most influenced by the birth weight of the male. What's most surprising here is that, when it comes to determing antler size of mature males, it didn't really matter whether males had been eating a low or high energy diet ('Energy') throughout their life

![image](https://user-images.githubusercontent.com/95881308/174356911-32e0dcf2-3de1-4c5f-97c4-1eacf9ea46f6.png)

### B. 5.5-year-olds: 
* Like in 4.5-year-olds, antler size of 5.5-year-old males was most influenced by the birth weight of the male. The father of the individual male ('SID') was the second highest ranked feature. Also, eating a low or high energy diet ('Energy') was not an important feature in predicting antler size of 5.5-year-olds.

![image](https://user-images.githubusercontent.com/95881308/174356922-f911d2bd-3fa6-4241-b419-e0aa2b9bc340.png)


## [Project 2: Predicting Winners of UFC Fights](https://github.com/sont5413/UFC-Fight-Data)
### Predicting Winners of UFC Fights
I built 2 classification models to predict the winner of a UFC fight based on age, height, and so on of the "red" fighter and the "blue fighter.
* Random Forest 
* Gradient Boosting

The Random Forest  model had the least mean absolute error and differed from the observed winner about 40% of the time.  In other words, it predicted the correct winner about 60% of the time!


#### Figure. Clearly no feature alone has huge explanatory power. In fact, most have very little explanatory power (roughly ≤ 0.03). However, the number of UFC fights a fighter had previously "BPrev" had the most predictor power.

![image](https://user-images.githubusercontent.com/95881308/177015092-8a2329ed-2c68-43e5-9e70-3e13c80a5441.png)

## [Project 3: Deer density and demographic trends from spotlight survey data at TMD installations collected between 2007 and 2021]https://github.com/sont5413/TMD-Deer-Demographics-From-Past-Surveys

#### Figure 1. Estimated deer density (acres per deer) at four TMD installations between 2007 and 2021.  The optimal deer density for this region of Texas (15 acres/deer) is represented by a horizontal line.
![image](https://user-images.githubusercontent.com/95881308/179097714-b0b64a36-6ae8-43b8-bbf8-9f03ecb779f5.png)

#### Figure 2. Estimated Buck to Doe ratio at four TMD installations between 2007 and 2021.  The optimal buck to doe ratio is 1.0 and is represented by a horizontal line.
![image](https://user-images.githubusercontent.com/95881308/179098076-713689e1-9e88-4076-a5e5-9b1ce700198f.png)

#### Figure 3. Estimated Fawn to Doe ratio at four TMD installations between 2007 and 2021.  An excellent fawn to doe ratio is 1.0 and is represented by a horizontal line.
![image](https://user-images.githubusercontent.com/95881308/179098087-43ffa255-f0ad-4806-89e9-940958627b92.png)

## [Project 4: Assessing Antler and Body Size of Mature Deer at Four Military Bases in Texas](https://github.com/sont5413/Deer-Herd-Characteristics---TMD)
### I assessed mean antler and body size of mature (>= 4.5 years) male white-tailed deer at four military bases in Texas

## A. Data
* This is a patchy dataset of white-tailed deer harvest data dating back to 2008. The metric used for antler size is total mean beam length.  Dressed body mass is the metric for body size.

## B. Goal:
* Determine if antler and body size of mature males changes over time and differs among training sites.
* Determine how large the sample sizes are for each site and year.

Figure 1. Mean antler size with 95% confidence intervals of mature males at four military bases in Texas.

![image](https://user-images.githubusercontent.com/95881308/174489405-4d3a9d69-c965-4c0b-9aae-a2ef57d13605.png)

Figure 2. Mean body size with 95% confidence intervals of mature males at four military bases in Texas.

![image](https://user-images.githubusercontent.com/95881308/174489428-a63b8603-41ce-46ea-9fa7-a39e23147b0e.png)

## C. Implications:
* You can see how small the sample sizes are just bases on how wide the confidence intervals are for some sites and seasons.
* Bowie has the largest sample sizes and therefore highest confidence in estimates for mean antler size and body size.

### a. Body Size:
* For the 2021 season, Swift can be interpretted as having the largest body size among mature deer.  While Maxey has a similar estimate for mean body size, the confidence intervals are too wide to interpret with confidence.
* Body size of mature males appears to remain stable at Bowie.
* Based on data from 2019 and 2021, it might be that mature males at Swift are a bit larger than the other sites.

### b. Antler Size:
* Bowie appears to have slightly larger antler size of mature males compared to Maxey.  However, there confidence intervals overlap so the comparison is with low confidence.
* Overall, antler size of mature males is similar among the four sites. I would be curious to see what these trends looked like with much more data.


## [Project 5: Analyzed Factors Influencing Body and Antler Size Relationships in White-tailed Deer: Project Overview](https://github.com/sont5413/Deer-scaling-relationships)
* Analyzed the degree to which maternal attributes (i.e., litter type and mother's age) and dietary energy influence body:antler size scaling relationships in white-tailed deer.
* Analyzed these relationships at two levels: 1) through the entire lifespan of individuals, and 2) at 5 different age groups (i.e., 1.5, 2.5, 3.5, 4.5, and 5.5).
* antler size and body size were log transformed in the .csv


#### Figure 1. Predicted regressions summarizing relationships between body mass and antler mass for male white-tailed deer fed either a low energy diet (L) or standard energy diet (S) in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654752-fd61734b-f805-4ac9-9022-4ad25e9c69da.png)


#### Figure 2. Predicted regression lines depicting the relationship between body mass and antler mass for male white-tailed deer aged 1.5 years fed either a low energy diet (L) or standard energy diet (S) and born to either a multiples or singleton litter in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654947-df38b97f-eae9-449f-9668-426da6bee2ed.png)



## [Project 6: Analyzed COVID-19 case rates for the month of January 2021 across 5 states that showed the highest increase in new cases](https://github.com/sont5413/CovidCasesJAN21)
* I analyzed an intercepts and slopes linear mixed effect model with State as the random factor.
* I also analyzed the 95% confidence interval of the fixed effect slope to conclude if rates vary among states. 
* My results show that the rate of exponential growth does not vary across the states. 
* The slope estimate for all five states (5.02) has a tight 95% confidence interval (4.28 to 5.75) that does not overlap zero (See Table 2, “Fixed Effects”).  
* Trellis plots of the data also show similar rates across all five states (See ancillary reporting on the last page of this report).
* I estimated a single model instead of a model for all 5 states in order to decrease the probability of committing a Type I error.

![image](https://user-images.githubusercontent.com/95881308/150697008-2fa3e27e-3c78-405d-b9a2-dc4bfdb85ea2.png)



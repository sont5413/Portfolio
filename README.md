# Willis Sontheimer Portfolio


## [Project 1: Predicting the Winner of a UFC Fight](https://github.com/sont5413/UFC-Fight-Data)
I built 3 models to predict the winner of a UFC fight based on age, height, and so on of the "red" fighter and the "blue fighter.
* Random Forest 
* Linear Regression
* Gradient Boosting
#### The Random Forest Classifier model had the least mean absolute error and differed from the observed winner about 40% of the time.  In other words, it predicted the correct winner about 60% of the time - At least it's better than guessing!

## [Project 2: Analyzed Factors Influencing Body and Antler Size Relationships in White-tailed Deer: Project Overview](https://github.com/sont5413/Deer-scaling-relationships)
* Analyzed the degree to which maternal attributes (i.e., litter type and mother's age) and dietary energy influence body:antler size scaling relationships in white-tailed deer.
* Analyzed these relationships at two levels: 1) through the entire lifespan of individuals, and 2) at 5 different age groups (i.e., 1.5, 2.5, 3.5, 4.5, and 5.5).
* antler size and body size were log transformed in the .csv


#### Figure 1. Predicted regressions summarizing relationships between body mass and antler mass for male white-tailed deer fed either a low energy diet (L) or standard energy diet (S) in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654752-fd61734b-f805-4ac9-9022-4ad25e9c69da.png)


#### Figure 2. Predicted regression lines depicting the relationship between body mass and antler mass for male white-tailed deer aged 1.5 years fed either a low energy diet (L) or standard energy diet (S) and born to either a multiples or singleton litter in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654947-df38b97f-eae9-449f-9668-426da6bee2ed.png)



## [Project 3: Analyzed covid case rates for the month of January 2021 across 5 states that showed the highest increase in covid19 cases](https://github.com/sont5413/CovidCasesJAN21)
* I analyzed an intercepts and slopes linear mixed effect model with State as the random factor.
* I also analyzed the 95% confidence interval of the fixed effect slope to conclude if rates vary among states. 
* My results show that the rate of exponential growth does not vary across the states. 
* The slope estimate for all five states (5.02) has a tight 95% confidence interval (4.28 to 5.75) that does not overlap zero (See Table 2, “Fixed Effects”).  
* Trellis plots of the data also show similar rates across all five states (See ancillary reporting on the last page of this report).
* I estimated a single model instead of a model for all 5 states in order to decrease the probability of committing a Type I error.

![image](https://user-images.githubusercontent.com/95881308/150697008-2fa3e27e-3c78-405d-b9a2-dc4bfdb85ea2.png)



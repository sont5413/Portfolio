# Willis Sontheimer Portfolio

## [Project 1: Factors Influencing Antler Size in Male White-tailed-Deer](https://github.com/sont5413/Predictors-of-Antler-Size-in-White-tailed-Deer)

![image](https://user-images.githubusercontent.com/95881308/197414332-b63d3c9c-1810-4ee7-94ac-6720c01d1ddd.png)

### I wanted to see what features influence antler size of white-tailed deer.
* Data: This is a unique dataset from a captive colony of white-tailed deer with known age, antler mass (kg), and maternal / paternal parentage.
* Each male was fed ab libitum one of two kinds of pelleted feed that differed in digestible energy, but had similar protein percentage (16%) from the time they were weaned. The standard energy diet 'S' had 2.65 kcal/g of dietary energy and the low energy diet 'L' had 1.77 kcal/g of dietary energy.

## Methods: 
* Model building and selection: linear regression, random forest (rf), gradient boosting (gb), and extreme gradient boosting (xgbr) models
* Tuned hyperparameters via grid search
* Feature importance: compare and contrast feature importances from ML models
  * The xgbr model achieve the lowest MAE after tuning, which was lower than the linear regression model. 

## Findings 

### A. Important features from the XGBR model: 
![image](https://user-images.githubusercontent.com/95881308/206016737-c7e7d951-6408-4aeb-a2e3-3d4bfecaecd8.png)

Body Mass was the most important feature and far and away more predictive than any of the other features.

## [Project 2: I assessed the effects of environmental factors on estimates of deer density from spotlight surveys](https://github.com/sont5413/Environmental_effects_deer_survey_estimates)

#### Project Summary: 
The environmental factors below do not signiciantly influence estimates of deer density made from spotlight surveys.  Temperature was found to be the most influential predictor from a multiple linear regression model (MLR) and two machine learning models (random forest and gradient boosting).  The R2 of the selected linear model was poor (~ 0.10).  However, temperature was found to be a statistically significant predictor (p < 0.001).  The selected MLR found that for every 1 degree fahreheit increase in temperature, there was a 0.80 decrease in the deer density. Environmental factors: 

* month of the year (numerical)
* temperature (continuous variable)
* wind (binary)
* cloud cover (index)
* rain (binary)
* snow (binary)
* fog (binary)
* moon phase

#### Dataset: 

I found this dataset through google's public dataset search.  This is deer spotlight survey data collected by the Department of the Interior in Great Smoky Mountains National Park from 1993-2003.

## [Project 3: Assessing effects of precipitatio and temperature (with time lags) on deer body mass](https://github.com/sont5413/Environmental_influences_on_deer_body_mass)

### I analyzed the effects of annual precipitation and temperature, with timelags ranging from 0-5 years, on body size in white-tailed deer.
  * I analyzed these effects separately in females and males.

## [Project 4: Predicting Number of Fatalities from Tornadic Events](https://github.com/sont5413/tornado)

![image](https://user-images.githubusercontent.com/95881308/197412724-3d32f019-969e-4338-bb2b-126346c17040.png)

Image of the 1999 Bridge Creek–Moore tornado, which is the strongest tornado ever recorded, globally. It affected the Oklahoma City, Oklahoma metropolitan area.

### I wanted to see what features from a tornado predict  number of fatalities
* Data: This is a dataset maintained by the National Oceanic and Atmospheric Administration (NOAA) of all recorded tornados since 1951.

#### Methods: 
* Model selection: Split data into test and train datasets and evaluate model perforamnce by mean absolute error (MAE). Evaluate performanc of random forest (rf), gradient boosting (gb), and xgboosting (xgb) regressor models.  The rf regressor model had the least MAE.
* Feature importance: Assess important features of the rf regressor model

#### Findings: 

![image](https://user-images.githubusercontent.com/95881308/197559293-dd65eebf-49eb-4194-8ce3-f52ff67d0d5a.png)

* A tornado's magnitude was the most important feature in predicting number of fatalities from a tornado.  Tornado length was nearly as predictive as magnitude.

## [Project 5: Predicting Winners of UFC Fights](https://github.com/sont5413/UFC-Fight-Data)
## Predicting Winners of UFC Fights
I built 2 classification models to predict the winner of a UFC fight based on age, height, and so on of the "red" fighter and the "blue fighter.
* Random Forest 
* Gradient Boosting

The Random Forest  model had the least mean absolute error and differed from the observed winner about 40% of the time.  In other words, it predicted the correct winner about 60% of the time!


## Findings:

![image](https://user-images.githubusercontent.com/95881308/177015092-8a2329ed-2c68-43e5-9e70-3e13c80a5441.png)

* Clearly no feature alone has huge explanatory power. In fact, most have very little explanatory power (roughly ≤ 0.03). However, the number of UFC fights a fighter had previously ('BPrev') had the most predictor power.

## [Project 6: Deer density and demographic trends from spotlight survey data at TMD installations collected between 2007 and 2021](https://github.com/sont5413/TMD-Deer-Demographics-From-Past-Surveys)

![image](https://user-images.githubusercontent.com/95881308/197414710-269af222-4655-49b4-8100-c58f23e4cd53.png)

### I assessed deer density and herd composition trends from spotlight survey data collected between 2007 and 2022.

#### Figure 1. Estimated deer density (acres per deer) at four military training sites in Texas between 2007 and 2022.  A management goal for these herds is to maintain deer densities between 10 and 20 acres per deer, which is represented by the red shaded area.
![image](https://user-images.githubusercontent.com/95881308/194447278-e269791f-9084-451b-b7fa-ade77108d64f.png)

#### Figure 2. Estimated buck to doe ratios at four military training sites in Texas between 2007 and 2022.  A management goal for these herds is to maintain buck to doe ratios at roughly 0.5, which is represented by a horizontal line.
![image](https://user-images.githubusercontent.com/95881308/194447510-c1242a22-831e-413a-843a-ff092ca15f46.png)

#### Figure 3. Estimated Fawn to Doe ratio at four military training sites in Texas between 2007 and 2021.  A healthy fawn to doe ratio is 0.75 and is represented by a horizontal line.
![image](https://user-images.githubusercontent.com/95881308/194447716-2d0587d0-5d42-489c-b8a3-d663da4d3166.png)

## [Project 4: R Shiny apps that I have built](https://github.com/sont5413/R-Shiny-Apps)
#### Fish species and capture location data viz:
   https://willis-sontheimer.shinyapps.io/Fish_app/

#### Water-quality trends at TMD training sites: 
   https://willis-sontheimer.shinyapps.io/Water-quality/
   

#### Deer demographic trends at TMD training sites: 
   https://willis-sontheimer.shinyapps.io/Deer_density_by_year_and_training_site/

## [Project 7: Assessing Antler and Body Size of Mature Deer at Four Military Bases in Texas](https://github.com/sont5413/Deer-Herd-Characteristics---TMD)
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
* You can see how small the sample sizes are just based on how wide the confidence intervals are for some sites and seasons.
* Bowie has the largest sample sizes and therefore highest confidence in estimates for mean antler size and body size.  

## [Project 8: Analyzed Factors Influencing Body and Antler Size Relationships in White-tailed Deer: Project Overview](https://github.com/sont5413/Deer-scaling-relationships)
* Analyzed the degree to which maternal attributes (i.e., litter type and mother's age) and dietary energy influence body:antler size scaling relationships in white-tailed deer.
* Analyzed these relationships at two levels: 1) through the entire lifespan of individuals, and 2) at 5 different age groups (i.e., 1.5, 2.5, 3.5, 4.5, and 5.5).
* antler size and body size were log transformed in the .csv


#### Figure 1. Predicted regressions summarizing relationships between body mass and antler mass for male white-tailed deer fed either a low energy diet (L) or standard energy diet (S) in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654752-fd61734b-f805-4ac9-9022-4ad25e9c69da.png)


#### Figure 2. Predicted regression lines depicting the relationship between body mass and antler mass for male white-tailed deer aged 1.5 years fed either a low energy diet (L) or standard energy diet (S) and born to either a multiples or singleton litter in a captive population of white-tailed deer.
![image](https://user-images.githubusercontent.com/95881308/150654947-df38b97f-eae9-449f-9668-426da6bee2ed.png)

## [Project 9: Analyzed COVID-19 case rates for the month of January 2021 across 5 states that showed the highest increase in new cases](https://github.com/sont5413/CovidCasesJAN21)
* I analyzed an intercepts and slopes linear mixed effect model with State as the random factor.
* I also analyzed the 95% confidence interval of the fixed effect slope to conclude if rates vary among states. 
* My results show that the rate of exponential growth does not vary across the states. 
* The slope estimate for all five states (5.02) has a tight 95% confidence interval (4.28 to 5.75) that does not overlap zero (See Table 2, “Fixed Effects”).  
* Trellis plots of the data also show similar rates across all five states (See ancillary reporting on the last page of this report).
* I estimated a single model instead of a model for all 5 states in order to decrease the probability of committing a Type I error.

![image](https://user-images.githubusercontent.com/95881308/150697008-2fa3e27e-3c78-405d-b9a2-dc4bfdb85ea2.png)



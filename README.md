
Repository for the COGS108 group final project at UCSD. 
___

In this project, we explore the relationship between health conditions in individuals across income levels in different regions in the United States as clinical and environmental factors can affect an individuals access to healthcare and to environments conducive to healthy lifestyles. With lower income individuals possessing less access to these benefits, it is more difficult for them to lead healthy lifestyles. As a result, a trend has developed wherein lower income individuals tend to have a greater prevalance of health issues, such as obesity and heart disease. Due to the heterogeneity of income across the United States, geographic location can be a confounding variable in this trend as well. 

Within the project, we conducted data cleaning of datasets obtained from the IRS and CDC as well as exploratory data analysis. Using this data, we modeled the data using multivariate linear regression, random forest regression, and K-Nearest neighbour regression with geographic location and health statistics as the predictors and income as the target value. Out of the three models, the random forest regression was able to achieve an $R^2$ value of 0.9962 while the other models performed poorly. 

From this we were able to model the relationship between obesity rates in individuals across income levels in different regions in the United States; however, the underlying data may not truely represent all individuals, causing a slight discrepancy between this model and the true relationship between income and health statistics. It should be noted that individuals without insurance, those that do not file tax returns, and/or others would be not accurately reflected in the data from the CDC and IRS. 

This repository contains our project proposal, data and EDA checkpoint, and our final project notebooks. 

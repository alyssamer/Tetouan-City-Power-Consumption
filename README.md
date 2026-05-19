# Predicting Tetouan City Power Consumption 

Originally a project for my course Statistical Learning and Big Data, we had to use several regression techniques to model and predict power consumption in three distribution zones in Tetouan, Morocco. The data features include the DateTime values every 10 minutes in each zone, as well as temperature, humidity, wind speed, general diffuse flows, and diffuse flows. I first separated the data into training and testing sets, did my exploratory data analysis, then created each of the models and compared their performance.


## Methods Used
- Multiple Linear Regression
- LASSO 
- Ridge Regression
- Random Forest
- Gradient Boosting



## Results
Gradient boosting (XGBoost) had the lowest RMSE & best R^2
      - Zone 1 --- RMSE: 1086 --- R^2: 97.69%
      - Zone 2 --- RMSE: 778 --- R^2: 97.78%
      - Zone 3 --- RMSE: 779 --- R^2: 98.62%
      s
Random forest performed very similarly, is more interpretable and not as computationally expensive so it likely would be chosen model
      - Zone 1 --- RMSE: 1170 --- R^2: 97.31%
      - Zone 2 --- RMSE: 867 --- R^2: 97.24%
      - Zone 3 --- RMSE: 865 --- R^2: 98.28%



## Files
Tetouan-City-Power-Consumption/
- dataset
        - Tetouan City power consumption.csv - CSV used
- tetuoancityQ.qmd - quarto document with full code and output 
- .gitignore - removes quarto's extra outputs
- .gitattributes - classifies .qmd as r code
- README.md



## Original Code: May 2026
# Concrete_Compressive_Strength_Prediction

![image](https://user-images.githubusercontent.com/112232080/231859156-5d51d25f-6f31-49c3-bdfa-2c404165e2e9.png)


### Introduction
The aim of the analysis is to build a regression model that predicts the concrete compressive strength based on different features. The dataset used includes features such as cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, fine aggregate, age (in days), and the target variable, concrete compressive strength.

### Data Preparation and Visualization
Before building the model, it is important to prepare and visualize the data. Data preparation includes cleaning the dataset, handling missing values, and dealing with outliers if any. Visualizing the data can be done using appropriate plots to explore the distribution of features and relationships with the target variable. In this analysis, scatter plots were used to check for relationships between features and the target variable.

Additionally, the normality of the target variable was checked using Jarque Bera Test. Multicollinearity was also checked among the features to ensure that the predictors were not highly correlated.

### Regression Model Building
Multiple regression models were used to predict the concrete compressive strength. These models include:

• LinearRegression: A simple linear regression model that minimizes the sum of squared errors between the target variable and the predicted values using a linear function.

• Ridge: A linear regression model that adds a penalty term to the sum of squared errors to prevent overfitting.

• Lasso: A linear regression model that adds an L1 penalty to the sum of squared errors to promote sparsity.

• ElasticNet: A linear regression model that combines L1 and L2 penalties to balance between Ridge and Lasso models.

• DecisionTreeRegressor: A non-parametric model that uses a decision tree to make predictions.

• RandomForestRegressor: A decision tree-based model that uses a combination of decision trees to make predictions.

• SVR: A support vector machine-based model that finds the hyperplane that best separates the data points in a high-dimensional space.

• GradientBoostingRegressor: A model that builds an ensemble of decision trees to make predictions using a gradient boosting algorithm.

• AdaBoostRegressor: A model that builds an ensemble of weak decision trees to make predictions using an adaptive boosting algorithm.

GridSearchCV was used to tune the hyperparameters of the models. Mean squared error, mean absolute error, and r2 score were used to evaluate the performance of the models. Additionally, homoscedasticity and normality of residuals were checked to ensure that the models met the assumptions of linear regression. Autocorrelation was also checked using the Durbin-Watson test.

## Conclusion
In conclusion, the best-performing model was selected based on the evaluation metrics. The limitations of the analysis and areas for future work can be discussed as well. The approach used in this analysis can be applied to similar regression problems in other domains as well.

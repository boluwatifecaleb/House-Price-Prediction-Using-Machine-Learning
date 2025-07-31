# House-Price-Prediction-Using-Machine-Learning

A machine learning model that predicts house prices based on features like year built, year remodelled, and total basement square footage using Python, pandas, scikit-learn, linear regression, and other techniques.

Problem Statement

To accurately predict the price of a house for buyers (so they do not feel exploited), sellers, and real estate professionals through relevant house features and historical data

Here are some of the features used in the dataset:

- `TotalBsmtSF` – Total basement area (sq ft)

- `YearRemodeled` – Year the house was remodelled (or same as YearBuilt if never remodelled)

- `YearBuilt` – Original construction date

- Algorithm: Linear Regression

- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

- Evaluation Metrics:

  - R² Score: `0.7057`

  - Mean Absolute Error (MAE): `~$28,229`

  - Where the mean price is: `~$177,083`

 

- Steps taken

- I cleaned the data by checking for missing values and dropped them where necessary, as replacing them with the mean value could have caused a false impression of the data.

- Then I checked for skewed data and any form of outliers in my data so I do not have issues along the line. I removed outliers and corrected the skewed data with a log transformation.

- I used a heatmap to see the correlations between the various features and dropped the totally irrelevant ones, as this prevents overfitting so my model could be used on a totally new dataset that it has not seen.

- I checked for OLS assumptions but did not really notice anyone.

- I also one-hot encoded the categorical data and dropped the first row of each of them to prevent multicollinearity.

- The model had an accuracy of 0.7249 during training but when tested was 0.7057, which shows that there is no overfitting or underfitting but can definitely be improved, as 29% of the data is not accounted for.

- The model achieved a score of 0.70, which means it correctly explains about 70% of the variation in house prices.

 




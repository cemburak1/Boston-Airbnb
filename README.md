# Boston-Airbnb
## Medium post:
https://medium.com/@591480co/boston-airbnb-data-analysis-b7dded7e523b



## Main Questions Answered:
- What is the price range of listings?
- Quality of data(in terms of missing values)
- How do pricing change per neighbourhood?
- What percentages do the amenities such as Wi-fi appear?
- What are the price determinants of Boston listings?


## Business Understanding
The goal of this project is to understand the underlying trends of Airbnb data in Boston by analysing average prices for each neighbourhood, proportion of amenities and determinants of pricing.

## Data Understanding
- Histograms of the price and the price per accommodate.
- Percentage of null values in numerical and categorical features.
- Histograms of numerical features.
- Number of data points per category in categorical features.
- Percentage of properties that offer each amenity.

## Data Preperation
- Creation of the variable price for accommodation.
- Elimination of variables with more than 95% of null values.
- Filling in the null values with the median in numerical characteristics.
- Filling in the null values with the mode in categorical characteristics.
- Creation of dummy variables for all categorical characteristics.
- Detection and elimination of outliers with Isolation Forest.

## Modelling
Linear regression & random forest are applied in order to find out the pricing determinants of Boston 

## Evaluation
RMSE is the evaluation metric

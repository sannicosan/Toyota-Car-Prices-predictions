# Summary
## Title
Toyota-Car-Prices-predictions
## Business Goal
The main objective of this business case was to be able to predict used car prices within a 10% of it's market value (i.e acurracy of at least 90%)

## Methodology

We have treated the problem as a regression problem, with `_price_` as the target variable and the rest as the dependent variables.
We have converted all categorical and ordinal variable to numeric ones to fit all these data to a regression model suitable for the business case. 

We chose a Linear Regression model (multivariate). With it, we can make predictions about the price on new unseen data, with an accuracy of around 92%! 

## Metrics - KPI

The business criteria was to estimate car prices within 10% of it's actual market sell price. Since the exercise required a regression problem, we can use the coefficient of determination $R^2$ as a KPI for the desired accuracy.
Additionally, we supported our analysis on a second metric: the _Mean Absolute Error_ it for comparison among models (baseline vs best).

At the end, we could report a **KPI of 92%** after the evaluation of our model.

## Recommendations
* It is much better to rely on a regression model that can predict car prices wiht a high accuracy instead of having sales team members do it. _Conclusion:_ The forecast process can be easily automated!!
* Bring in more and more data from past sales to fine-tune the model and obtain an even better performance

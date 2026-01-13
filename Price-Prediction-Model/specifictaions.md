### Problem statement##
Crop price prediction is a critical task in the agricultural sector, as it helps farmers, traders, and policymakers make informed decisions. 
## Objective##
As a business (school), we would like to know when to make purchases of produce to maximize profit.
## Decision + stakeholders##
The decision involves determining optimal purchase timing for produce based on predicted price trends. Stakeholders include school administrators, procurement officers, and financial managers who are responsible for budget allocation and cost management.
## Constraints:##
- Data sources are not of African context, so we are using a Indian dataset for the time being
- Limited historical data availability
- Seasonal variations in crop prices
- Market volatility and external economic factors

## Data Card: ##
### Dataset Overview ###
Each row in the data set represents the price of a commodity on a given date in a given market. The dataset contains the following columns:
- **date**: The date of the price record (format: YYYY-MM-DD)
- **district**: The district where the market is located
- **market**: The name of the market
- **commodity**: The name of the commodity (crop)
- **price**: The price of the commodity at that market on that date (in local currency per unit)
A shape of; **4819 rows × 5 columns**

## Baseline Model##
- A baseline model using Linear Regression will be implemented to predict crop prices based on historical data. The model will be trained on a portion of the dataset and evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to assess its predictive accuracy. 
- Scikit-learn library in Python will be used for model implementation.
- Further enhancements may include feature engineering, hyperparameter tuning, and exploring more complex models like Random Forest or Gradient Boosting.

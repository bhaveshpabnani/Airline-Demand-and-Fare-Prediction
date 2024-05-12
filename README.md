# Airline Revenue Management Prediction

This repository contains the solution for the Airline Revenue Management challenge, which aims to predict demand and prices for flights using historical booking data and schedule/market information. The challenge focused on building a statistical model to forecast future bookings and corresponding fares, considering various factors influencing customer demand and pricing decisions.

## Problem Statement

The airline industry operates in a competitive environment where accurate decision-making is crucial for maximizing profitability. Revenue Management (RM) involves analyzing demand and setting optimal prices for flights, considering factors such as historical data, market conditions, and customer willingness to pay. The challenge tasked participants with building a model to predict demand and prices for flights, utilizing historical booking data and schedule/market information.

## Dataset Description

The provided dataset includes:
1. **Booking Data**: Historical bookings by Flight ID, departure date, Origin & Destination ID, Cabin, Booking class of service, Dep Time & Arr Time, Booking count, and average booking fare.
2. **Flown Passenger Data**: Final count of flown passengers for the first 12 months of flights, along with average fare (at cabin level).
3. **Schedule & Market Data**: Flight ID details, competition flight details for the same Origin & Destination ID, and airline market share.

## Approach

### Data Preprocessing
- Explored and preprocessed the datasets, handled missing values, and encoded categorical variables.
- Merged relevant datasets to create a unified dataset for analysis and modeling.

### Feature Engineering
- Extracted relevant features such as time to departure, seasonality indicators, competition metrics, and market share.
- Engineered additional features like cancellation/no-show rate and overbooking to enhance model performance.

### Model Training
- Utilized statistical models such as regression, time series analysis, and machine learning algorithms to predict demand and prices for flights.
- Split the data into training and validation sets, and trained the model using the first 12 months of data.
- Evaluated model performance using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and forecast accuracy.

### Prediction and Validation
- Used the trained model to forecast bookings and corresponding fares for the last 3 months of flights.
- Compared model predictions with actual data to validate the accuracy and reliability of the model.
- Interpreted model outputs and identified factors influencing demand and pricing decisions.

## Results and Insights

- Presented the model outputs, including demand forecasts and price estimations, for different flights at various days to departure.
- Analyzed the features contributing to demand prediction and pricing decisions, considering factors like seasonality, trends, and market conditions.
- Discussed the model's performance and potential areas for improvement, such as incorporating price elasticity and continuous pricing strategies.

## Conclusion

The solution developed for the Airline Revenue Management challenge provides a robust framework for predicting demand and prices for flights, enabling airlines to optimize revenue management strategies. By leveraging advanced analytics techniques and historical data, the model offers valuable insights into customer behavior and market dynamics, facilitating data-driven decision-making in the airline industry.

---

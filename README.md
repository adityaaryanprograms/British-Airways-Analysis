# British Airways Analysis

## Problem Statement
British Airways is facing a significant challenge in maintaining customer satisfaction amidst an increasingly competitive aviation market. Moreover, the volatility in customer booking patterns exacerbated by fluctuating economic conditions and pandemic-induced travel uncertainties complicates demand forecasting. We can address these issues through a robust data science approach that combines sentiment analysis of customer reviews with predictive modeling of flight bookings.

## Description
The customer booking dataset contains 50,000 records with 14 columns describing the channel of sales, details of the flight as well as the customer's preferences. Each review in the customer reviews dataset had a text infront irrelevant to the analysis which was removed. The reviews were cleaned further by removing HTML tags, accented and special characters among other impurities. The 'booking_origin' column in the customer booking dataset had some '(not set)' values which needed to be eliminated. Oversampling was used balance the dataset since the customers who booked a flight were much less than the customers who did not. Sentiment analysis was performed to understand reviews. Multiple classification techniques were employed to forecast the booking of flights.

## Outcome
Reviews were analysed to gain valuable insights on customer service and XGBoost model was tuned to predict flight booking with 81% accuracy.

## Key Skills Used
Pandas, Web Scraping, Pre-processing, Variable Analysis, Transformation, Sentiment Analysis, Encoding, Oversampling, Classification, Ensemble, Boosting, Hyperparameter Tuning

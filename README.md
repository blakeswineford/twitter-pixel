# Predicting Lift with Twitter's 1st Party Advertising Pixel
## Internally known as Lower Funnel Click ID (LFCLID) 

# Introduction
This project explored the potential lift in conversion tracking an advertiser could see when switching from 3rd party pixels to Twitter's 1st party pixel. By leveraging synthetic data to simulate user interactions and applying OLS regression modeling, we aimed to provide advertisers with insights into the benefits of using Twitter's first party pixel. 

# Data
Synthetic Data
Generated to simulate the behavior of users interacting with ads. This dataset reflects user interactions under two distinct scenarios:

- Interactions without the benefits of Twitter's first party pixel.
- Interactions with the incorporation of Twitter's first party pixel.
- Real Data (Twitter's actual user data, which was used to validate the model built on synthetic data). 

# Methodology
- Synthetic Data Generation: Synthetic data was meticulously crafted to mirror user interactions with ads, considering factors like views, click-through rates, site visits, and conversions.

 - Modeling with OLS Regression: The relationship between features like site visits, proceeded to checkout, etc., and conversions were modeled using OLS regression. This helped in understanding the potential lift in conversions.

 - Validation on Real Data: The performance of the model built on synthetic data was validated using real Twitter data. The model's accuracy was measured using the Root Mean Squared Error (RMSE) metric.

# Results
- The model achieved an RMSE of approximately 6.87 on the synthetic datasets.
- Based on the analysis with Twitter's real data the model suggests a potential lift of 15% in conversion tracking when transitioning to Twitter's 1st party pixel.

# Dependencies
Python
pandas
numpy
statsmodels


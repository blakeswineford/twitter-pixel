# Predicting Lift with Twitter's 1st Party Advertising Pixel
Internally known as Lower Funnel Click ID (LFCLID) 

# Introduction
This project explored the potential lift in conversion tracking an advertiser could see when switching from 3rd party pixels to Twitter's 1st party pixel. By leveraging synthetic data to simulate user interactions and applying OLS regression modeling, the goal was to provide advertisers with data around the benefits of implementing Twitter's 1st party pixel.  

# Methodology
- Synthetic Data Generation: Synthetic data was created to mirror user interactions with ads, considering only causal factors like views, click-through rates, site visits, and conversions.

 - Modeling with OLS Regression: Using statsmodels.api OLS regression.

 - Validation on Real Data: The performance of the model built on synthetic data was validated using real Twitter data.

# Results
- Based on the analysis with Twitter's real data the model suggests a potential lift of 15% in conversion tracking when transitioning to Twitter's 1st party pixel.

# Dependencies
Python
pandas
numpy
faker
statsmodels



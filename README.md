# Car-Prediction-Model-ML-

1.INTRODUCTION
In the dynamic world of automobile sales, predicting the right price of a used car is both a business necessity and a data-driven challenge. This project aims to forecast car prices using a Linear Regression model based on various real-world attributes such as brand, year of manufacture, mileage, fuel type, transmission, and ownership. This real-industry use-case helps apply machine learning techniques meaningfully, enhancing your learning portfolio and preparing you for real-world data science roles.

2.DATASET OVERVIEW
• Total entries: 4,340 • Features included: o Car Brand & Model (processed to extract brand) o Year of Manufacture o Kilometers Driven o Fuel Type o Transmission o Owner Type o Location o Selling Price (Target Variable) • Missing Values: None found • Encoding: Label Encoding used for categorical features • Scaling: StandardScaler applied on all features

3.EXPLORATORY DATA ANALYSIS (EDA)
Key insights from visual analysis: • Price Distribution: Selling prices are right-skewed, with most cars priced under ₹1,000,000. • Brand-wise Pricing: Brands like Maruti, Hyundai, Honda, and Toyota show higher median resale values. • Correlations: o year has a strong positive correlation with selling_price o km_driven has a weak negative correlation Visuals used: • Histogram of selling_price • Boxplots grouped by brand • Correlation heatmap of numerical features

4.MODEL DEVELOPMENT
• Model Used: Linear Regression • Preprocessing Steps: o Label Encoding for categorical variables: fuel, seller_type, transmission, owner, brand o Feature scaling using StandardScaler • Train-Test Split: 80% training, 20% testing

5.MODEL EVALUATION
Metric Value Mean Absolute Error (MAE) ₹221,866 Mean Squared Error (MSE) ₹183,761,321,763 Root Mean Squared Error (RMSE) ₹428,674 R² Score (Goodness of Fit) 0.398 • The model explains approximately 39.8% of the variation in selling prices.

6.CONCLUSION
The linear regression model provides moderate accuracy in predicting car prices. While it performs well in recognizing general trends, it may miss out on complex non-linear relationships.

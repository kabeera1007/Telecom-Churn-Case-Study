# Telecom-Churn-Case-Study

## Business Objective

The business objective is to predict customer churn in the last (i.e., the ninth) month using data from the first three months. To reduce churn, telecom companies need to predict which customers are at high risk of leaving.

## Steps Followed:

1. **Load and inspect data**: Import necessary libraries and the dataset.
2. **EDA and feature engineering**: Handle missing values, visualize the data, create relevant features, remove outliers, and derive churn.
3. **Model building and evaluation**: Apply PCA to select relevant features, use Random Forest and Logistic Regression models, evaluate their performance, and select the best model for predicting churn.

## Key Factors Influencing Churn

In our examination, we have identified key factors that influence churn. These factors include:

- **total_ic_mou_8**: Total incoming call minutes of usage in the action phase.
- **total_rech_amt_diff**: Total recharge amount difference.
- **total_og_mou_8**: Total outgoing call minutes of usage in the action phase.
- **arpu**: Average revenue per user.
- **roam_ic_mou_8**: Roaming incoming call minutes of usage in the action phase.
- **roam_og_mou_8**: Roaming outgoing call minutes of usage in the action phase.
- **std_ic_mou_8**: STD incoming call minutes of usage in the action phase.
- **std_og_mou_8**: STD outgoing call minutes of usage in the action phase.
- **av_rech_amt_data_8**: Average recharge amount in the action phase.

## Ways to Minimize Churn

To minimize churn, the following strategies can be implemented:

1. **Offer tailored discounts** to customers based on their usage patterns.
2. **Introduce extra internet services** as part of recharge packages.
3. **Engage in personalized conversations** with customers to meet their specific needs.
4. **Reduce tariffs for data usage** and improve 2G coverage in areas without 3G access.
5. **Extend the reach of the 3G network** to areas currently lacking 3G connectivity.

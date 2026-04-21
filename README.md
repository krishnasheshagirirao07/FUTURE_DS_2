## Task 2: Customer Retention & Churn Analysis 📉

### Objective
To analyze customer data for a subscription-based business to identify churn patterns, determine retention drivers, and build a predictive model to flag at-risk customers.

### Tools Used
* **Python** (Pandas, Matplotlib, Seaborn, Scikit-Learn) - Data Cleaning, EDA, and Machine Learning
* **Power BI** - Interactive Retention Dashboard

### Key Business Insights
1. **Contract Risk:** Customers on **Month-to-Month** contracts have a significantly higher churn rate (over 40%) compared to those on 1-year or 2-year contracts.
2. **Price Sensitivity:** High `MonthlyCharges` and `TotalCharges` are the leading predictors of customer cancellation.
3. **Tenure Drop-off:** The highest risk of churn occurs within the first 5 months. Customers who surpass this threshold exhibit strong long-term loyalty.
4. **Payment Methods:** Users paying via **Electronic Check** are disproportionately more likely to churn.

### Machine Learning Model
* Built a **Random Forest Classifier** to predict customer churn.
* Achieved an accuracy of **~78%**, successfully identifying the top features driving customer attrition: Total Charges, Monthly Charges, and Tenure.

### Recommendations
* **Incentivize Annual Contracts:** Offer strategic discounts or premium features to convert Month-to-Month users into 1-year commitments.
* **Targeted Onboarding:** Implement a high-touch customer success program for the first 5 months to prevent early drop-off.
* **Payment Method Nudges:** Encourage Electronic Check users to switch to Auto-Pay (Credit Card/Bank Transfer) by offering a small one-time discount.

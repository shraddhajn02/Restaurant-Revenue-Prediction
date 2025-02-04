# Restaurant-Revenue-Prediction

Restaurants generate revenue through multiple factors, and understanding the key drivers helps in optimizing pricing strategies, promotions, and marketing campaigns. This project explores the impact of different variables on revenue prediction and evaluates the performance of machine learning models for accurate forecasting.

*Dataset*

The dataset used in this project consists of various restaurant attributes:
Input Variables (Features):
> Number_of_Customers - The total number of customers visiting the restaurant. <br>
> Menu_Price - The average price of items on the menu. <br>
> Marketing_Spend - The budget allocated for marketing campaigns. <br>
> Cuisine_Type - Type of cuisine offered. <br>
> Average_Customer_Spending - The average spending per customer. <br>
> Promotions - Special deals or discounts offered. <br>
> Reviews - Customer feedback and ratings. <br>

Target Variable (Output):
> Monthly_Revenue - The total revenue generated in a month.

1. Data Preprocessing
Read the dataset using pandas.
Handle missing values and remove unnecessary columns.
Encode categorical variables such as cuisine type.
Perform feature selection using statistical methods and correlation analysis.

2. Exploratory Data Analysis (EDA)
Analyze the distribution of numerical features.
Identify correlations between variables.
Visualize revenue trends using:
Histograms
Pairplots
Boxplots
Correlation heatmaps

3. Feature Engineering
Transform skewed data for better model performance.
Normalize/standardize features.
Create new derived variables if necessary.

4. Model Selection & Training
Split the dataset into training and testing sets.
Train multiple regression models:
Linear Regression
Lasso Regression
Ridge Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
K-Nearest Neighbors (KNN)
Use GridSearchCV for hyperparameter tuning.

5. Model Evaluation
Evaluate models using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared Score (R²)
Compare model performances and select the best approach.
Results & Insights

**Top Features Impacting Revenue:**
Marketing Spend and Promotions significantly impact revenue growth.
Customer Reviews and Average Spending play a vital role in revenue variation.
Menu Pricing should be optimized for better profitability.
 
 *Best Performing Model:*
Based on RMSE and R² score, the Random Forest Regressor provided the most accurate revenue predictions.
Feature selection improved model performance and reduced overfitting.
 
 *Business Implications:*
Restaurants should focus on customer engagement strategies like discounts and promotions.
Marketing spend should be optimized based on ROI analysis.
Analyzing customer reviews can help improve services and attract repeat customers.

*****Technologies & Skills Used*****

**Programming & Libraries:**
Python (pandas, numpy, scipy, matplotlib, seaborn, sklearn)

*Machine Learning Techniques:*
Regression models (Linear, Lasso, Ridge, Decision Trees, Random Forest, Gradient Boosting, KNN)
Feature Selection and Hyperparameter Tuning

*Data Analysis & Visualization:*
Exploratory Data Analysis (EDA)
Correlation Analysis & Feature Engineering
Statistical Analysis (scipy.stats)

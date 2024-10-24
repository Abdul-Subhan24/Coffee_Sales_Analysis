# Coffee Sales Analysis
This repository contains an analysis of coffee sales data aimed at uncovering trends, patterns, and sales predictions using machine learning algorithms. The project was implemented using **Google Colab**, where the code and analysis were executed in a cloud environment. The primary goal is to optimize business decisions based on data-driven insights.

# Key Objectives:
-  **Analyze histori****cal sales data** to identify trends and seasonality.
-  **Develop predictive models** to forecast future coffee sales based on past performance.
-  **Identify key factors** influencing sales to provide actionable insights for decision-makers.
- **Perform visual data analysis** to explore patterns in coffee consumption, payment methods, and customer preferences.

# Tools and Technologies:
- **Platform:** Google Colab
**Programming Language:** Python
- **Libraries:**
-    **Data Analysis:** Pandas, NumPy
    **Visualization:** Matplotlib, Seaborn
    **Machine Learning & Modeling:** Scikit-learn, XGBoost, Random Forest
    **Model Tuning:** GridSearchCV for hyperparameter optimization
    - **Data Processing:** Datetime, Scipy, StandardScaler

**Project Workflow:**
1.  **Data Preprocessing:**
- Loaded sales data and cleaned it by handling missing values and formatting date-time features.
Categorical features were encoded for model readiness.

2. **Exploratory Data Analysis (EDA):**
- Conducted visualizations such as sales over time, breakdowns of sales by product type, and payment methods.
Used pairplots and boxplots to detect outliers and examine relationships between features.

3. **Feature Engineering:**
- Extracted meaningful features from the data, such as time-based variables (day, month, year) to improve model accuracy.

4. **Model Building:**
- Multiple regression models were trained, including:
    L- inear Regression
    - Random Forest
    - Gradient Boosting
    - XGBoost
    - K-Nearest Neighbors
- Models were evaluated using R-squared and Mean Squared Error (MSE) as performance metrics.

5. **Hyperparameter Tuning:**
- Used GridSearchCV to fine-tune the Random Forest and XGBoost models for improved performance, adjusting parameters like n_estimators, max_depth, and min_samples_split.

6. **Cross-Validation:**
- Applied cross-validation techniques to ensure the models’ performance was consistent across different datasets.

7. **Feature Importance:**
- Visualized the most important features contributing to the predictive power of the models using feature importance  - plots from Random Forest and XGBoost.

**Key Insights:**
- **Seasonality in Sales:** Monthly and weekly trends were identified, indicating seasonal spikes in sales.
- **Top Selling Products:** Certain products consistently outperformed others, providing insights into customer preferences. 
- **Payment Preferences:** A comparison between cash and card payments revealed trends that could help optimize payment processing systems.

**Conclusion:**
The Coffee Sales Analysis project successfully demonstrated the use of machine learning techniques to predict future sales trends. The **Random Forest** and **XGBoost** models provided the best predictive performance, with hyperparameter tuning significantly improving accuracy. These models, combined with visual insights, offer valuable guidance for inventory management and marketing strategies.

The analysis highlights the importance of seasonal patterns and payment methods in understanding customer behavior, offering businesses the ability to make more informed, data-driven decisions.


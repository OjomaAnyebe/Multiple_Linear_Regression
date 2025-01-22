# Multiple Linear Regression

This repository contains my solution to a multiple linear regression exercise as part of my data science learning journey on Udemy. The exercise involves analyzing a real estate dataset to understand how property size and construction year influence price.

---

## About the Exercise

### Dataset:
The dataset provided, `real_estate_price_size_year.csv`, includes information about real estate properties, such as:
- **Dependent Variable (Target):**
  - `price`: The selling price of the property.
- **Independent Variables (Features):**
  - `size`: The size of the property in square meters.
  - `year`: The year the property was constructed.

### Objective:
- Build a **Multiple Linear Regression** model to predict property prices.
- Analyze how the size and construction year affect pricing trends.

---

## Tools and Libraries Used

This exercise utilizes the following Python libraries:
- **`numpy`**: For numerical computations.
- **`pandas`**: For loading, exploring, and manipulating the dataset.
- **`matplotlib` and `seaborn`**: For visualizing relationships between variables.
- **`statsmodels`**: For performing regression analysis and summarizing results.

---

## Key Highlights of the Exercise

1. **Exploratory Data Analysis (EDA):**
   - Summarized the dataset to understand the distribution of features and the target variable.

2. **Model Creation:**
   - Defined `price` as the dependent variable and `size` and `year` as independent variables.
   - Added a constant term to account for the intercept.
   - Built a regression model using **Ordinary Least Squares (OLS)**.

3. **Model Interpretation:**
   - Evaluated the summary report to understand:
     - Coefficient values for each feature.
     - P-values to assess statistical significance.
     - R-squared value to evaluate model performance. 

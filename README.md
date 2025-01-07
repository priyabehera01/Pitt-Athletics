# Pitt Athletics Off-Field Analytics Project

## Project Overview
The goal of this project is to predict whether customers will renew their season tickets for the next year. By analyzing customer data, we aim to identify key factors that influence season ticket renewal decisions. This is a classification problem, where the two categories are:
- Customers who will renew their season tickets next year.
- Customers who will not renew their season tickets next year.

## Key Insights
- **Age & Gender:** Specific age groups (36-45, 46-55, and 56-65) and gender (male) had a significant impact on whether a customer would renew their ticket.
- **Price Type & Purchase Month:** Customers who purchased IA tickets or bought tickets in "other" months (not January or February) were less likely to renew.
- **Data Analysis:** Exploratory Data Analysis (EDA), including box plots, helped identify relationships between different features (such as age and gender) and renewal likelihood.
- **Clustering:** Clustering analysis supported the predictive models, revealing that specific age and gender combinations had higher renewal rates.

## Methodology
1. **Exploratory Data Analysis (EDA):**
   - Visualized trends and relationships using various plots, such as box plots, to understand the distribution of features and identify potential predictors.
   
2. **Clustering Analysis:**
   - Performed clustering to see how different customer segments were distributed and how they related to season ticket renewal.

3. **Predictive Modeling:**
   - Built and evaluated multiple models, including Logistic Regression, Ridge, Lasso, and ElasticNet.
   - Used cross-validation to ensure the robustness of the models.
   - Model 4, which included all available features, performed the best and provided the most reliable predictions.

## Skills Gained
- Data Preprocessing: Cleaning and transforming raw data for analysis.
- Exploratory Data Analysis (EDA): Visualizing and interpreting data to uncover trends and patterns.
- Clustering: Segmenting customers into groups based on their features.
- Predictive Modeling: Using logistic regression and regularization techniques to build and evaluate models.
- Cross-validation: Assessing model performance and avoiding overfitting.

## Key Findings
- Middle-aged customers (36-65) and males are more likely to renew their season tickets.
- IA ticket types and purchases in non-peak months (other than Jan-Feb) were associated with lower renewal rates.
- Predictive models and clustering showed consistent results, confirming the significance of the identified predictors.

## Future Directions
This project enhanced my skills in data analysis and predictive modeling. In the future, I plan to expand this analysis to more complex models and apply these techniques to health data, helping to uncover patterns that can be used to improve public health and well-being.

## Tools and Libraries Used
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib & seaborn (for data visualization)

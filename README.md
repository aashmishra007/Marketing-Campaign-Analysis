# Marketing-Campaign-Analysis
Marketing Campaign Analysis using Applied Data Science (Python)

**Project Overview**
This project focuses on analyzing marketing campaign and customer data to identify key factors influencing customer purchasing behavior and campaign acceptance. The analysis applies exploratory data analysis (EDA), statistical techniques, feature engineering, and data visualization to generate actionable business insights.
The project was completed as part of an Applied Data Science with Python program and is aligned with real-world marketing analytics and business decision-making use cases.

**Objectives**
Understand customer demographics and spending behavior
Analyze performance across different sales channels (web, store, catalog)
Evaluate factors influencing campaign acceptance
Test business-driven hypotheses using data and statistics

**Dataset Description**

The dataset includes:
Customer demographics (age, education, marital status, country)
Income and spending behavior across multiple product categories
Purchase channels (web, store, catalog)
Marketing campaign responses
Customer complaints and engagement indicators

**Key Steps Performed**

1. Data Cleaning & Preprocessing
Verified correct data types for variables such as income and customer registration date
Handled missing income values using group-based imputation (education & marital status)
Cleaned and standardized categorical variables

2. Feature Engineering
Created meaningful features to enhance analysis:
Customer Age
Total Children (kids + teens)
Total Spending across all product categories
Total Purchases across all sales channels

3. Exploratory Data Analysis (EDA)
Used histograms and boxplots to study distributions
Identified skewness and outliers in spending variables
Applied winsorization to treat extreme outliers

4. Encoding & Transformation
Applied one-hot encoding for nominal categorical variables
Used ordinal encoding for ordered categories such as education

5. Statistical & Correlation Analysis
Generated correlation heatmaps to identify relationships between variables
Tested business hypotheses related to:
Online vs in-store purchasing behavior by age
Impact of children on online shopping preference
Sales channel cannibalization
Regional performance comparison (USA vs Rest of World)

6. Key Insights
Customer age and household composition influence channel preference
Certain product categories significantly contribute to total revenue
Digital channels show strong adoption but do not fully replace physical stores
Campaign acceptance varies by demographic and regional factors
(Insights are supported using visualizations and statistical reasoning.)

**Tools & Technologies Used**
a. Python
b. Pandas, NumPy
c. Matplotlib, Seaborn
d. SciPy
e. Jupyter Notebook

📂 Repository Structure
├── data/
│   └── marketing_campaign.csv
├── notebooks/
│   └── marketing_campaign_analysis.ipynb
├── README.md

**How to Run the Project**
a. Clone the repository
b. Install required libraries:
    pip install pandas numpy matplotlib seaborn scipy
c. Open the Jupyter Notebook:
    jupyter notebook
    Run marketing_campaign_analysis.ipynb

**Key Learning Outcomes**
Practical experience in EDA and statistical analysis
Hands-on feature engineering for business analytics
Applying statistics to test real-world business hypotheses
Translating data findings into actionable insights

👤 Author
Ashwani Mishra
Business & Data Analyst | Data Science & AI (In Progress)
LinkedIn: https://www.linkedin.com/in/ashwanimishra

# Marketing-Campaign-Analysis
Marketing Campaign Analysis using Applied Data Science (Python)

**Project Overview**<br>
This project focuses on analyzing marketing campaign and customer data to identify key factors influencing customer purchasing behavior and campaign acceptance. The analysis applies exploratory data analysis (EDA), statistical techniques, feature engineering, and data visualization to generate actionable business insights.
The project was completed as part of an Applied Data Science with Python program and is aligned with real-world marketing analytics and business decision-making use cases.

**Objectives**<br>
a. Understand customer demographics and spending behavior<br>
b. Analyze performance across different sales channels (web, store, catalog)<br>
c. Evaluate factors influencing campaign acceptance<br>
d. Test business-driven hypotheses using data and statistics<br>

**Dataset Description**

The dataset includes:<br>
a. Customer demographics (age, education, marital status, country)<br>
b. Income and spending behavior across multiple product categories<br>
c. Purchase channels (web, store, catalog)<br>
d. Marketing campaign responses<br>
e. Customer complaints and engagement indicators<br>

**Key Steps Performed**<br>

1. Data Cleaning & Preprocessing:<br>
Verified correct data types for variables such as income and customer registration date<br>
Handled missing income values using group-based imputation (education & marital status)<br>
Cleaned and standardized categorical variables<br>

2. Feature Engineering:<br>
Created meaningful features to enhance analysis:<br>
Customer Age<br>
Total Children (kids + teens)<br>
Total Spending across all product categories<br>
Total Purchases across all sales channels<br>

3. Exploratory Data Analysis (EDA)
Used histograms and boxplots to study distributions<br>
Identified skewness and outliers in spending variables<br>
Applied winsorization to treat extreme outliers<br>

4. Encoding & Transformation<br>
Applied one-hot encoding for nominal categorical variables<br>
Used ordinal encoding for ordered categories such as education<br>

5. Statistical & Correlation Analysis<br>
Generated correlation heatmaps to identify relationships between variables<br>
Tested business hypotheses related to:<br>
Online vs in-store purchasing behavior by age<br>
Impact of children on online shopping preference<br>
Sales channel cannibalization<br>
Regional performance comparison (USA vs Rest of World)<br>

6. Key Insights<br>
Customer age and household composition influence channel preference<br>
Certain product categories significantly contribute to total revenue<br>
Digital channels show strong adoption but do not fully replace physical stores<br>
Campaign acceptance varies by demographic and regional factors<br>
(Insights are supported using visualizations and statistical reasoning.)<br>

**Tools & Technologies Used**<br>
a. Python<br>
b. Pandas, NumPy<br>
c. Matplotlib, Seaborn<br>
d. SciPy<br>
e. Jupyter Notebook<br>

📂 Repository Structure<br>
├── data/<br>
│   └── marketing_campaign.csv<br>
├── notebooks/<br>
│   └── marketing_campaign_analysis.ipynb<br>
├── README.md<br>

**How to Run the Project**<br>
a. Clone the repository<br>
b. Install required libraries:<br>
    pip install pandas numpy matplotlib seaborn scipy<br>
c. Open the Jupyter Notebook:<br>
    jupyter notebook<br>
    Run marketing_campaign_analysis.ipynb<br>

**Key Learning Outcomes**<br>
Practical experience in EDA and statistical analysis<br>
Hands-on feature engineering for business analytics<br>
Applying statistics to test real-world business hypotheses<br>
Translating data findings into actionable insights<br>

👤 Author<br>
Ashwani Mishra<br>
Business & Data Analyst | Data Science & AI (In Progress)<br>
LinkedIn: https://www.linkedin.com/in/ashwanimishra

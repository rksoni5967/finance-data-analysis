# finance-data-analysis
This is data analysis project which shows insight about the bank personal loan data.

# Data Analysis for Loan Purchase Likelihood at AllLife Bank

## Project Overview
This project was undertaken for AllLife Bank to analyze the performance of a recent marketing campaign targeting liability customers. The campaign achieved a conversion rate of over 9%, and the goal was to provide insights and recommendations to help the marketing team improve future campaigns by identifying potential customers more likely to purchase a loan.

As a **Data Analyst**, my role was to explore the data, generate insights, and provide actionable recommendations to guide the marketing team's targeting efforts.

## Problem Statement
AllLife Bank’s marketing team wants to increase the success rate of future campaigns by identifying patterns in customer demographics and behaviors that are linked to a higher likelihood of loan purchases.

The goal of this analysis is to:
- Understand customer characteristics and behaviors that led to loan purchases.
- Identify key factors influencing the conversion rate.
- Recommend segments of customers for future targeted campaigns.

## Approach
1. **Exploratory Data Analysis (EDA)**:
   - **Data Understanding**: I started by reviewing the dataset, which contains customer demographics, account details, and past interactions.
   - **Descriptive Statistics**: Summarized data to understand the distribution and spread of variables like age, income, and account balance.
   - **Customer Segmentation**: Performed segmentation to identify clusters of customers with similar characteristics and behaviors.

2. **Data Cleaning**:
   - Handled negative values by imputing where necessary and removing any inconsistencies.
   - Encoded categorical variables (account information, education) to prepare them for analysis.

3. **Correlation Analysis**:
   - Conducted correlation analysis between different customer features and loan purchase likelihood.
   - Focused on identifying patterns like the relationship between income levels and loan purchases.

4. **Customer Profiling**:
   - Created profiles for customers who purchased loans versus those who didn’t, analyzing factors such as:
     - Age distribution
     - Income levels
     - Account balance
     - Employment status
     - Previous engagement with the bank

5. **Key Insights**:
   - Discovered patterns that indicate customers in certain income brackets or account balance ranges are more likely to purchase loans.
   - Identified that customers who had engaged with previous campaigns or maintained a higher account balance had a higher probability of conversion.

6. **Visualization**:
   - Created visualizations (box plots, histograms, pie charts, and heatmaps) to clearly present data trends and relationships. This helped highlight the customer groups most likely to purchase a loan.

## Tools & Technologies
- **Python**: For data manipulation and analysis
- **Pandas & NumPy**: For data cleaning, transformation, and statistical calculations
- **Matplotlib & Seaborn**: For data visualization and exploratory analysis
- **Excel**: For data review and summarization

## Results & Findings
- **Demographics**: Customers aged between 30-45 with an income range of $40,000-$80,000 were more likely to purchase loans.
- **Account Behavior**: A significant portion of loan buyers had account balances above a certain threshold, indicating financial stability.
- **Previous Engagement**: Customers who had responded positively to past campaigns had a higher conversion rate in this campaign.

## Repository Structure
- `Bank_Personal_Loan_Modelling-checkpoint.csv`: Contains cleaned datasets used for analysis.
- `Loan_data.ipynb` : Jupyter notebooks showing the step-by-step data analysis.
- `README.md`: Project overview and details.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/rksoni5967/finance-data-analysis.git

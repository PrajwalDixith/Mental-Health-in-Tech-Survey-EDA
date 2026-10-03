Mental Health in Tech – EDA Assignment 


� Objective: 
Explore and analyze the 2014 Mental Health in Tech Survey dataset to uncover patterns, 
trends, and insights related to attitudes and experiences regarding mental health in the tech 
workplace. 

This project solves following tasks

Section A: Data Understanding and Preprocessing 
✅ Task 1: Load and Inspect the Data 
● Load the dataset into a Pandas DataFrame. 
● Display the first 10 rows. 
● Print basic info and check for missing values. 

✅ Task 2: Data Cleaning 
● Identify and handle: 
○ Invalid age values (e.g., < 18 or > 100) 
○ Inconsistent or vague gender responses 
○ Missing or null values 
● Drop any irrelevant columns (e.g., timestamps, free-text comments, etc.). 
Expected Deliverables: 
● Cleaned dataset 
● Summary of cleaning decisions (bullet points) 
Section B: Univariate Analysis 

✅ Task 3: Demographic Overview 
● Age distribution (histogram) 
● Gender distribution (bar chart) 
● Country-wise response count (top 10) 

✅ Task 4: Mental Health Context 
● Count of respondents with/without: 
○ Family history of mental illness 
○ Past treatment 
○ Current work interference due to mental health 
○ Self-employment status 
Expected Deliverables: 
● Plots + short interpretations 
Section C: Bivariate Analysis 

✅ Task 5: Gender & Treatment 
● Bar plot: Treatment status by gender 

✅ Task 6: Country & Work Interference 
● Group by country: % of respondents who said mental health interferes with work 

✅ Task 7: Company Size & Benefits 
● Analyze relationship between no_employees and: 
○ Availability of mental health benefits 
○ Wellness programs 
○ Knowledge of care options 
Expected Deliverables: 
● Grouped bar plots / cross-tabulations + insights 
Section D: Attitudes Toward Mental Health 

✅ Task 8: Discussion Comfort 
● % of people willing to discuss mental health with: 
○ Coworkers 
○ Supervisors 
○ During interviews 

✅ Task 9: Mental vs Physical Health Perceptions 
● Analyze and visualize: 
○ Do employees feel mental health is taken as seriously as physical health? 
○ Compare across gender and employer type (tech_company) 

✅ Task 10: Anonymity & Consequences 
● How do people perceive: 
○ Anonymity if seeking help? 
○ Potential negative consequences? 
● Break this down by employer type (tech_company) and remote workers. 
Expected Deliverables: 
● Stacked bar plots or grouped charts + written summaries 
Section E: Geographic & Remote Work Insights 

✅ Task 11: U.S. State-wise Patterns 
● Top 5 U.S. states with highest % of people who have received treatment 
● Map-based or bar plot visual 

✅ Task 12: Remote Work Effect 
● Compare mental health treatment rates and perception of support between: 
○ Remote workers vs Non-remote workers 
Expected Deliverables: 
● Visual comparisons + written insights 
Section F: Predictive Insights 

✅ Task 13: Correlation Analysis 
● Encode categorical variables and compute correlations (e.g., with treatment, 
interference) 
● Heatmap of correlations 

✅ Task 14: Strong Predictors 
● Use logistic regression or decision tree (optional advanced step) to identify: 
○ Most predictive factors for whether someone sought treatment 
Expected Deliverables: 
● Correlation matrix 
● Optional model summary or feature importance plot 
Section G: Summary & Recommendations 

✅ Task 15: Final Observations 
● Summarize 5-7 key insights from your EDA. 
● Suggest 2-3 recommendations for tech companies to better support mental health. 

# Lead Conversion Prediction for EdTech Startup

[![View Project](https://img.shields.io/badge/View-GitHub%20Page-blue)](https://joelbenjohn.github.io/EdTech-Customer-Lead-Conversion-Prediction/)

This project involves building a predictive model for ExtraaLearn, an EdTech startup, to identify leads most likely to convert into paid customers. The analysis and models developed provide actionable insights to optimize marketing strategies and improve conversion rates.

---

## Project Overview

With the rapid growth of the EdTech sector, efficiently identifying high-potential leads has become crucial. This project addresses this challenge by exploring and analyzing lead data, running hypothesis tests, and building classification models to predict lead conversion.

### Key Objectives
- Analyze the impact of various factors (e.g., current occupation, interaction channels, profile completion) on lead conversion.
- Build and optimize machine learning models to accurately predict lead conversion.
- Provide actionable insights and strategic recommendations based on data-driven findings.

---

## Dataset

The dataset contains attributes related to leads and their interactions with ExtraaLearn, including:
- **ID**: Unique identifier for each lead.
- **Age**: Age of the lead.
- **Current Occupation**: Occupation status (Professional, Unemployed, Student).
- **First Interaction**: How the lead first interacted with ExtraaLearn (Website, Mobile App).
- **Profile Completion**: Percentage of profile completed (Low, Medium, High).
- **Website Visits**: Number of times the lead visited the website.
- **Time Spent on Website**: Total time spent on the website.
- **Page Views per Visit**: Average pages viewed per visit.
- **Last Activity**: Last recorded interaction with the lead (Email, Phone, Website).
- **Marketing Channels**: Flags indicating exposure to various marketing channels (Print, Digital, Referral).
- **Status**: Target variable indicating conversion (1 = Converted, 0 = Not Converted).

---

## Project Structure

- **EDA and Hypothesis Testing**: Conducted exploratory data analysis to uncover patterns and used Chi-Square tests to validate significant relationships between variables.
- **Data Preprocessing**: Managed missing values, treated outliers, and prepared data for modeling.
- **Model Building**: Trained and optimized Decision Tree and Random Forest classifiers. Evaluated models using metrics like accuracy, precision, recall, and F1-score.
- **Insights and Recommendations**: Provided data-driven recommendations to enhance marketing and engagement strategies based on model findings and hypothesis testing.

---

## Key Findings

1. **Current Occupation**: Professionals are more likely to convert compared to students and unemployed leads.
2. **First Interaction Channel**: Leads interacting through the website showed higher conversion rates than those using the mobile app.
3. **Modes of Interaction**: Phone interactions and website activities proved to be more effective for lead conversion.
4. **Marketing Channels**: Digital and referral-based channels had higher conversion rates compared to traditional print media.
5. **Profile Completion**: Leads with higher profile completion percentages were more likely to convert.

---

## Technologies Used

- **Python**: Data analysis, modeling, and visualization.
- **Pandas & NumPy**: Data manipulation and statistical analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning and model evaluation.
- **SciPy**: Statistical hypothesis testing.

---

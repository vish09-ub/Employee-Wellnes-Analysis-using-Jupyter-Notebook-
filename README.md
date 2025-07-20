# 🧠 Employee Wellness Analysis

This project explores mental health trends in the workplace using survey data. Through exploratory data analysis (EDA), the goal is to uncover patterns related to employee stress, stigma, awareness of mental health resources, and workplace support. The project is aimed at helping organizations build a healthier, more inclusive work culture.

## 📌 Project Overview

Mental health plays a crucial role in employee productivity and overall organizational well-being. This analysis provides insights into factors that influence mental health at work and identifies at-risk employee groups using real-world survey data.

### 🔍 Objectives

- Analyze mental health trends and workplace stressors.
- Identify employees who may need mental health support.
- Evaluate awareness and access to mental health resources.
- Understand the impact of family history, work interference, and stigma.
- Recommend actionable wellness strategies for HR and leadership.

## 🗂️ Dataset Overview

- **Responses**: 1,200+ survey responses
- **Attributes (27)**: Age, Gender, Country, Family History, Mental Health Treatment, Workplace Support, etc.

### Key Columns:
- `Age`, `Gender`, `Country`
- `treatment`, `family_history`, `work_interfere`
- `benefits`, `wellness_program`, `seek_help`
- `mental_health_consequence`, `phys_health_consequence`

## 🧹 Data Cleaning Steps

- Removed duplicates and empty rows
- Filtered valid age range (18–100)
- Handled missing values using imputation/mode
- Grouped gender into: Male, Female, Other
- Standardized inconsistent categorical responses (e.g., "yes", "Yes", "Y")

## 📊 Key Insights

- **34%+** have sought mental health treatment.
- Work interference and family history are strong predictors of treatment.
- Majority are unaware of workplace mental health benefits.
- Most employees feel more comfortable talking to coworkers than supervisors.
- Significant stigma still exists, especially in interview settings.

## 💡 Recommendations

- Improve communication about available wellness programs.
- Ensure anonymity in accessing mental health resources.
- Train managers to reduce stigma and promote openness.
- Launch awareness campaigns focused on younger and mid-level employees.
- Encourage mental health days and flexible policies.

## 🛠️ Tools Used

- **Excel**: Initial cleaning & standardization
- **Python (Jupyter Notebook)**: Data processing & visualization  
  - Libraries: `pandas`, `matplotlib`, `seaborn`
- **Canva**: Final report design & visualization




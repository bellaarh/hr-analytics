# 🏢 HR Analytics: Decoding Employee Attrition
**End-to-End Data Analysis using Python & Tableau**

## 📌 Project Overview
Employee turnover is a significant cost for any organization, impacting both operational efficiency and recruitment budgets. This project analyzes the **IBM HR Analytics Employee Attrition** dataset to uncover the root causes of why employees leave and identify key factors that drive retention. 

By transitioning raw HR data into actionable insights, this project provides a data-driven foundation for HR Partners and Management to formulate proactive retention strategies.

## 🛠️ Tech Stack & Workflow
* **Language:** Python
* **Libraries:** Pandas (Data Cleansing, Feature Engineering, Correlation Analysis)
* **Visualization:** Tableau Public (Interactive HRIS-style Dashboard)
* **Environment:** Jupyter Notebook / VS Code

## 📊 Key Business Insights
Through Exploratory Data Analysis (EDA) and correlation mapping, several critical insights were discovered:
1. **The "Smoking Gun" (OverTime):** Employees who frequently work overtime have a drastically higher flight risk. Correlation analysis proved this is the #1 driver of attrition in this dataset (Attrition Rate jumps to ~30% for those with overtime).
2. **The Commute Fatigue:** `DistanceFromHome` is the second strongest factor pushing employees to resign.
3. **Strongest Retention Factors:** Employees with higher `JobLevel`, higher `MonthlyIncome`, and older `Age` exhibit strong loyalty and the lowest attrition rates.

## 📈 Tableau Dashboard
The final output is an interactive, enterprise-grade Tableau Dashboard designed to mimic a real-world HR Information System (HRIS). It features Executive KPIs, Attrition drivers, and Demographic breakdowns.

🔗 **[https://public.tableau.com/views/IBMHRAnalyticsEmployeeAttritionPerformance_17834294014130/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]**

## 📂 Repository Structure
* `01_hr_attrition_eda.ipynb` : The main Python notebook containing data cleansing, feature engineering, and statistical correlation analysis.
* `WA_Fn-UseC_-HR-Employee-Attrition.csv` : The original raw dataset.
* `hr_attrition_cleaned_for_tableau.csv` : The processed and cleaned dataset exported for visualization.

## 💡 Strategic Recommendations for HR
* **Overtime Audit:** Strictly monitor and limit excessive overtime, especially in departments with high baseline attrition.
* **Flexible Work Arrangements:** Consider remote or hybrid work options to mitigate the commute fatigue for employees living far from the office.

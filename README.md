# Salifort-Motors-Capstone Project
Data professional Analysis for Salifort Motors

Author: Sulay Cay

Date: 13-April-2025

---
# 🧠 Employee Turnover Prediction – Salifort Motors

This project aims to identify key drivers of employee turnover at Salifort Motors and build predictive machine learning models to help HR reduce attrition and improve employee retention strategies.

---

## 📁 Project Structure

📂 Employee-Turnover-Prediction/ ├── HR_capstone_dataset.csv ├── Salifort_Motors_Employee_Turnover_Analysis.ipynb ├── Filled_Course_7_PACE_Strategy_Document.docx ├── Filled_Executive_Summary_Salifort_Motors.pptx └── README.md

---

## 📌 Project Objective

Salifort Motors is experiencing a high rate of employee turnover. This project uses Python to:
- Analyze employee data from various departments
- Identify key features contributing to attrition
- Build predictive models (Logistic Regression, Decision Tree, Random Forest, XGBoost)
- Recommend actionable insights for HR and leadership teams

---

## 📊 Data Overview

**Dataset:** `HR_capstone_dataset.csv`  
**Rows:** 14,999  
**Columns:** 10

| Column Name             | Description                                                  |
|------------------------|--------------------------------------------------------------|
| satisfaction_level     | Self-reported satisfaction score [0-1]                       |
| last_evaluation        | Last performance review score [0-1]                          |
| number_project         | Number of projects the employee worked on                    |
| average_monthly_hours  | Avg monthly work hours                                       |
| time_spend_company     | Years at the company                                         |
| work_accident          | 1 if the employee had a work accident, 0 otherwise           |
| left                   | 1 if the employee left, 0 otherwise                          |
| promotion_last_5years  | 1 if promoted in the last 5 years, 0 otherwise               |
| department             | Department name                                              |
| salary                 | Categorical: low, medium, high                               |

---

## 🔍 Key Findings

- Employees with low satisfaction and no promotions are more likely to leave.
- High average monthly hours correlate with higher turnover risk.
- Low salary is a strong indicator of potential departure.
- Feature importance from Random Forest and XGBoost validated these insights.

---

## 🧪 Models & Performance

| Model             | Accuracy | Notes                         |
|------------------|----------|-------------------------------|
| Logistic Regression | ~77%  | Baseline performance          |
| Decision Tree       | ~89%  | Strong, easy to interpret     |
| Random Forest       | ~91%  | Great balance of precision/recall |
| XGBoost             | ~92%  | Best performer overall        |

---

## ✅ Recommendations

- Improve satisfaction through employee engagement programs.
- Offer clearer promotion paths and career development.
- Monitor workload and reduce overwork in high-burnout departments.
- Consider salary benchmarking and reviews.
- Deploy predictive models in HR systems to flag high-risk employees.

---
## Power BI Visualizations 
![image](https://github.com/user-attachments/assets/1ab8c9bc-01f7-43b5-82a4-ceda230e30fd)

![image](https://github.com/user-attachments/assets/451714fb-3b97-4c11-afdd-73cc8c14ea17)

![image](https://github.com/user-attachments/assets/51329a73-b367-4bad-a6c3-31d6d1f10055)

![image](https://github.com/user-attachments/assets/aa39e7f1-eb8b-49fb-b84b-22f0059c0499)

![image](https://github.com/user-attachments/assets/b799e042-5ea9-4964-ad65-edf050a76988)

![image](https://github.com/user-attachments/assets/01792b20-8d44-4c7b-9ab0-c65e4fe4893c)

![image](https://github.com/user-attachments/assets/8efc8e5b-dd51-4431-8560-2fea75498007)

![image](https://github.com/user-attachments/assets/6f753c91-b566-44a0-942d-2b391688bbbc)







---

## Tableau Vizzes - Vizualizations



![image](https://github.com/user-attachments/assets/51491ee2-b57a-4103-9a8f-6032decfd20d)

![image](https://github.com/user-attachments/assets/1b3cc3f2-da3e-4674-9bab-d42691ac1551)

![image](https://github.com/user-attachments/assets/d1303c23-d63b-4240-b624-64862d079135)

![image](https://github.com/user-attachments/assets/385f6b68-555f-49de-87eb-dfe11c35881b)






---
## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Employee-Turnover-Prediction.git
   cd Employee-Turnover-Prediction


jupyter notebook Salifort_Motors_Employee_Turnover_Analysis.ipynb
PACE CAPSTONE LAB PROJECT JUPYTER NOTEBOOK 


[https://github.com/sulay01/Salifort-Motors-Capstone-Project/blob/main/Activity_%20Course%207%20Salifort%20Motors%20project%20lab.ipynb]

[https://github.com/sulay01/Salifort-Motors-Capstone-Project/blob/main/Exemplar_%20Course%207%20Salifort%20Motors%20project%20lab.ipynb]




pip install pandas numpy seaborn matplotlib scikit-learn xgboost



---

📄 Files
Salifort_Motors_Employee_Turnover_Analysis.ipynb: Full Python notebook

Filled_Course_7_PACE_Strategy_Document.docx: Project planning strategy

Filled_Executive_Summary_Salifort_Motors.pptx: Executive-facing summary presentation

Salifort_Motors_HR_Turnover_Report.pdf: One-page dark theme PDF report

HR_capstone_dataset.csv: Dataset used for the project

PowerBI_Visuals/: Contains PDF charts created in Power BI

Tableau Visualization 

---

## ✅ Conclusion
The Salifort Motors Employee Turnover Project demonstrates how data analytics and machine learning can be leveraged to tackle real-world HR challenges. Through comprehensive exploratory data analysis, predictive modeling, and data visualization, this project uncovered key drivers of attrition—such as low satisfaction, lack of promotion, excessive workload, and low compensation.

The predictive models, especially Random Forest and XGBoost, achieved high accuracy in forecasting employee turnover, offering HR departments actionable tools for early intervention. These insights empower leadership to take a proactive stance on employee retention, fostering a more engaged and stable workforce.

This project reflects the application of the full PACE (Plan, Analyze, Construct, Execute) framework, aligning business questions with data-driven decision-making. With strategic recommendations backed by visual storytelling in Power BI and Tableau, this capstone not only enhances operational awareness but also serves as a strong portfolio piece demonstrating end-to-end analytical proficiency.



---

📬 Contact
Author: Sulay Cay

LinkedIn: https://www.linkedin.com/in/sulay-cay-0589513a/


GitHub: https://github.com/sulay01

Tableau: https://public.tableau.com/app/profile/sulay.cay/vizzes
Salifort_Motors_HR_Employee_Turnover_By_Department



📚 License
This project is for educational purposes only and part of the Google Advanced Data Analytics Professional Certificate.



---


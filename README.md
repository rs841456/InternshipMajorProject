
# 🧠 HR Analytics - Predicting Employee Attrition

> 📊 A complete end-to-end data science project analyzing employee attrition using IBM HR data. Built as part of an internship at **Cognifyz Technologies**.

---

## 📌 Overview

Employee attrition — the loss of employees over time — is a key challenge for organizations. This project uses historical HR data from IBM to:

✅ Analyze trends and key reasons behind attrition  
✅ Predict employees likely to leave using ML models  
✅ Visualize insights through an interactive Power BI dashboard  

---

## 🎯 Objectives

- Understand employee behavior and attrition patterns
- Build predictive models using Python
- Create dashboards for HR to take data-driven decisions

---

## 🛠️ Tools & Technologies

| Tool / Library      | Purpose                                |
|---------------------|----------------------------------------|
| Python              | Data analysis and ML                   |
| Pandas, Seaborn     | Data cleaning and visualization        |
| Scikit-learn        | Logistic Regression, Decision Tree     |
| SHAP                | Feature importance & explainability    |
| Power BI            | Dashboard creation                     |
| Jupyter Notebook    | Interactive coding & documentation     |

---

## 📂 Folder Structure

```bash
HR-Attrition-Project/
│
├── 📄 WA_Fn-UseC_-HR-Employee-Attrition.csv   # Original dataset
├── 📄 Clean_HR_Attrition.csv                  # Cleaned dataset
├── 📄 DataCleaned.ipynb                       # Python notebook for analysis
├── 📄 DataCleaned.pdf                         # Notebook exported as PDF
├── 📄 DashboardHr.Data.pbix                   # Power BI Dashboard
├── 📄 HR-Employee-AttritionProjectReport.pdf  # Final project report
├── 📄 README.md                               # Project documentation (this file)
```

---

## 📈 Steps & Approach

### 1. Data Cleaning 🧹
- Removed duplicates, null values
- Encoded categorical features
- Saved cleaned data as `Clean_HR_Attrition.csv`

### 2. Exploratory Data Analysis 🔍
- Studied relationships between attrition and:
  - Age
  - Monthly Income
  - OverTime
  - Job Role
- Used `Seaborn` for visual insights

### 3. Model Building 🤖
- Models used:
  - Logistic Regression
  - Decision Tree Classifier
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
- Applied **SHAP** to interpret model decisions

### 4. Dashboard Development 📊
- Created with Power BI
- Visualized:
  - Department-wise attrition
  - Key feature impact
  - Filtering by gender, job role, income

---

## 📌 Key Insights

- Employees with **OverTime** are more likely to leave
- **Low Monthly Income** is a major risk factor
- **Younger age groups** show higher attrition
- Decision Tree model gave better transparency for HR use

---

## ✅ Results

- Achieved good prediction accuracy using both models
- Clear visualization using Power BI helped stakeholders
- SHAP analysis added explainability to the predictions

---

## 📎 Project Deliverables

| File Name                              | Description                             |
|----------------------------------------|-----------------------------------------|
| `WA_Fn-UseC_-HR-Employee-Attrition.csv`| Original dataset from IBM               |
| `Clean_HR_Attrition.csv`               | Final cleaned dataset                   |
| `DataCleaned.ipynb`                    | Full Python code for analysis & ML      |
| `DataCleaned.pdf`                      | Read-only version of the notebook       |
| `DashboardHr.Data.pbix`                | Power BI interactive dashboard          |
| `HR-Employee-AttritionProjectReport.pdf` | Final PDF report with summary, visuals  |

---

## 🧑‍💼 Author

**Rajan Kumar**  
Intern, Cognifyz Technologies  
📅 July 2025  
✉️ *rajan@example.com* (Add your real contact if needed)

---

## 📜 License

This project is for educational and internship purposes. Dataset © IBM.  
Power BI dashboard and code can be reused with credits.

---

## 🙏 Acknowledgements

- IBM for the open dataset  
- Cognifyz Technologies for internship support  
- OpenAI (ChatGPT) for guidance on report and formatting

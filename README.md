# 💼 HR Analytics – Predict Employee Attrition

### 🎯 Objective
Analyze HR data to **identify key factors behind employee attrition** and **predict employees likely to leave**, enabling proactive retention strategies.

---

## 🧠 Overview
This project combines **Python-based machine learning** with **Power BI visualization** to uncover attrition trends and support HR decision-making.

**Main steps:**
1. Data Cleaning & EDA  
2. Model Building (Logistic Regression, Decision Tree, Random Forest)  
3. Explainability (SHAP values)  
4. Dashboard Visualization (Power BI)  
5. Strategic HR Recommendations (PDF)

---

## 🛠️ Tools & Libraries
**Python:** Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib, SHAP  
**Visualization:** Power BI  
**Reporting:** ReportLab  

---

## 📊 Model Results
| Model | Accuracy | ROC AUC | Key Insight |
|--------|-----------|----------|--------------|
| Logistic Regression | 0.748 | 0.799 | Best balance of accuracy and recall |
| Decision Tree | ~0.77 | Moderate | Simple, risk of overfitting |
| Random Forest | 0.837 | 0.755 | Highest accuracy but low recall for attrition |

**Top Features:**  
`OverTime`, `MonthlyIncome`, `YearsAtCompany`, `JobSatisfaction`, `EnvironmentSatisfaction`

---

## 📈 Power BI Dashboard
📂 `hr dashboard.pbix`

Interactive dashboard showing:
- Department-wise attrition  
- Salary & promotion impact  
- Employee demographics  
- Key KPIs (Attrition %, Avg. Income, Satisfaction)

---

## 📑 Deliverables
| File | Description |
|------|--------------|
| `HR Analytics - Predict Employee Attrition.ipynb` | Python notebook (EDA + ML) |
| `hr dashboard.pbix` | Power BI dashboard |
| `attrition_prevention_suggestions.pdf` | HR strategy report |
| `.png / .txt files` | Model evaluation visuals & reports |

---

# Credit Risk Analysis – Group 10 (DATA Wranglers)

Course: CSIS 503 – Data Science & Analytics  
Project:Final Capstone Project  
Team: Group 10 – Credit Risk Analysis  

---

## Project Overview
This project analyzes anonymized loan data to assess credit risk. Our goal was to identify the main factors driving default, evaluate portfolio risk distribution, and apply predictive models to classify loans by risk class.

---

## Dataset
Size: 7,577 rows × 13 variables (after cleaning)  
Key Features: Loan Type, Risk Class, Interest Rate, Total Balance, Principal, Risk Limit, Economic Sector  
Preparation:Removed duplicates, handled missing values, treated outliers, and engineered time-based features (`loan_age`, `maturity_length`).  

---

## Methodology
1. Data Preparation: Cleaning, preprocessing, feature engineering.  
2. Exploratory Data Analysis (EDA): Trends by sector, boxplots, distributions.  
3. Modeling: Logistic Regression, Random Forest, and XGBoost.  
4. Evaluation:Confusion matrix, accuracy, precision, recall, F1-score.  

---

## Key Findings
- Risk is concentrated in specific sectors.  
- Logistic Regression achieved ~97% accuracy, though minority classes remain difficult to classify.  
- Tree-based models provided robustness and confirmed similar drivers of risk.  
- Top drivers include loan principal, balance, and economic sector.  

---

## Team Roles
- Adrian L. Diadula: Data wrangling, coordination, video facilitation,Github Submission  
- Metasebia Fekadu Wondimu: Data gathering, EDA, regression analysis  
- Randy Boateng: Methodology presentation, regression techniques, Python libraries  
- Eboigbe Harrison: Slide design, presentation of results  
- Ametelah Abubeker Aliy: Report editing, insights/limitations 

---

## Deliverables
- [Notebook: Group 10 CreditRiskAnalysis.ipynb](./Group%2010%20CreditRiskAnalysis.ipynb)  
- [Final Report (DOCX)](./Final%20Group%2010_CRA.docx)  
- [Role Summary (DOCX)](./Final%20Group10_Role_Summary.docx)  
- [Presentation (PPTX)](./Group%2010%20Presentation%20Credit%20Risk%20Analysis.pptx) 

---

## References
See full references in the Final Report document.


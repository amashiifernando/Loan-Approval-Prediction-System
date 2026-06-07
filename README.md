# Loan Approval Prediction Using Machine Learning

## Project Overview
This project develops a machine learning model to predict loan approval status based on applicant demographic, financial, and property-related information.

The study compares multiple machine learning algorithms and identifies the most important factors influencing loan eligibility.

---

## Objectives
- Identify key variables influencing loan approval  
- Develop machine learning models for loan prediction  
- Compare model performance using evaluation metrics  
- Improve consistency and efficiency in loan approval decisions  

---

## Dataset
The dataset represents loan applications from Dream Housing Finance and contains applicant information such as:

- Gender  
- Married  
- Dependents  
- Education  
- Self Employed  
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Loan Term  
- Credit History  
- Property Area  

---

## Data Preprocessing
- Missing value imputation  
- Label Encoding  
- One-Hot Encoding  
- Feature Scaling using StandardScaler  
- Train-Test Split  

---

## Models Evaluated
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)  

---

## 📈 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 86.18%   |
| Decision Tree       | 86.18%   |
| SVM                 | 85.37%   |
| Random Forest       | 84.55%   |
| Gradient Boosting   | 83.74%   |

---

## 🏆 Best Model
**Logistic Regression**

- Accuracy: 86.18%  
- F1-Score: 0.908  
- ROC-AUC: 0.848  

---

## Key Findings
- Credit History was the strongest predictor of loan approval.  
- Property Area, Marital Status, Education, and Income also had significant impact.  
- Logistic Regression provided the best balance between performance and interpretability.  

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

---

 ## Repository Contents
* `report/`: Contains the full project documentation. 
  [View the PDF Report](Loan_approval_prediction_project/report/loan_approval_prediction_report.pdf)
  
* `code/`: Contains the codes used for data processing and model fitting. 
  [View Notebook](Loan_approval_prediction_project/code/finalcode.ipynb)
  
* `dataset/`: Contains the dataset used. 
  [View Dataset](Loan_approval_prediction_project/dataset/traindataset.csv)

---

## Author

**Amashi Fernando**

Final-Year Applied Statistics Undergraduate
University of Colombo
Sri Lanka



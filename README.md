# Telco Customer Churn Analysis with AI/ML

**Student:** Vishal Pal  
**Project Type:** Data Analytics with AI/ML  
**Program Submission:** IBM SkillsBuild Data Analytics with AI Internship 2026

## Project Overview

This project analyzes customer churn for a fictional telecommunications company using the public IBM Telco Customer Churn sample dataset.

The project covers:

- Data loading and quality checks
- Data cleaning and type conversion
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data visualization
- Logistic Regression
- Random Forest classification
- Model evaluation using Accuracy, Precision, Recall, F1 and ROC-AUC
- Feature importance / explainability
- AI/ML-based churn risk scoring
- Business-oriented insights and recommendations

## Dataset

**Source:** IBM Telco Customer Churn Sample Dataset

Dataset URL:
https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

IBM's archived repository:
https://github.com/IBM/telco-customer-churn-on-icp4d

The dataset contains customer profile, service, contract, billing and churn information. It is provided as sample data for educational/analytics use.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Exploratory Data Analysis

## Project Files

1. `VishalPal_Telco_Churn_AI_Analytics.ipynb` — complete project code
2. `requirements.txt` — Python dependencies
3. `VishalPal_ProjectReport.docx` — project documentation
4. `README.md` — project overview and setup instructions

## How to Run

### 1. Install Python

Python 3.10 or newer is recommended.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

`VishalPal_Telco_Churn_AI_Analytics.ipynb`

### 4. Run all cells

The notebook first tries to download the dataset from the IBM public source. If internet access is unavailable, place `Telco-Customer-Churn.csv` in the notebook folder and run the notebook again.

## Expected Workflow

**Data → Cleaning → EDA → Feature Engineering → ML Models → Evaluation → Risk Scoring → AI-Assisted Insights**

## Important Note

This is an educational project. Churn probability is a model estimate, not a statement about a customer's actual future behavior. The project does not recommend making automated high-impact decisions about individual customers.

## Data Limitations

- The source is a sample snapshot.
- It is not a live production customer database.
- It does not contain a complete monthly time series for every customer.
- Associations found in the analysis should not be interpreted as causal relationships.

## References

IBM Telco Customer Churn repository:
https://github.com/IBM/telco-customer-churn-on-icp4d

IBM raw dataset:
https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

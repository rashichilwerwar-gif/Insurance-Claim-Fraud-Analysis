# Insurance Claim Fraud Analysis

## Project
**Insurance Claim Fraud Analysis**

This project was prepared for the **IBM SkillsBuild Data Analytics with AI Academic Internship Program**, conducted by BharatCares in association with AICTE.

## Project Description
The project analyzes an auto-insurance claims dataset and focuses on identifying patterns associated with potentially fraudulent claims. The dataset contains **975 records and 38 columns**. The workflow includes data inspection, cleaning, exploratory data analysis, preparation of numerical and categorical variables, and a machine-learning classification workflow.

IBM Watson Studio/Data Refinery can be used for data preparation and exploration, while Python/Jupyter is used for reproducible analysis and modeling.

## Dataset
Dataset used: **Auto Insurance Claims / insurance claims dataset**.

**Dataset link:** https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims

> If your internship portal supplied a different dataset URL, replace the link above with the exact URL used in your submission.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- IBM Watson Studio / Data Refinery
- SQL, Tableau, and spreadsheet tools for complementary analytics

## Files
- `Rashi_Chilwerwar_Insurance_Claim_Fraud_Analysis.ipynb` — complete analysis and machine-learning notebook
- `requirements.txt` — Python dependencies
- `Rashi_Chilwerwar_ProjectReport.docx` — project report
- `README.md` — project overview and execution instructions

## Setup and Run
1. Install Python 3.10+.
2. Open a terminal in the project folder.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Put the dataset CSV in the same folder as the notebook.
5. Open Jupyter Notebook:

```bash
jupyter notebook
```

6. Open the `.ipynb` file.
7. Update `DATA_FILE` to the exact CSV filename if necessary.
8. Run the notebook cells from top to bottom.

## Key Analysis
- Dataset structure and descriptive statistics
- Missing-value analysis
- Duplicate checking and removal
- Numerical and categorical feature analysis
- Fraud-class distribution
- Investigation of claim amounts, including a hypothesis around claims above $10,000
- Feature preprocessing
- Logistic Regression classification
- Accuracy, precision, recall, F1-score, and confusion matrix

## Expected Outcome
The notebook produces an auditable data-analysis workflow and a baseline classification model for fraud-related claim prediction. Model metrics depend on the exact dataset version and the preprocessing performed at runtime.

## Author
**Rashi Chilwerwar**

# Churn Prediction Executive Summary

A Python project for churn prediction in the SME energy sector. Includes data loading, feature engineering, Random Forest modeling, evaluation, and a business-friendly PowerPoint slide with SCQA framework. Outputs PPT/PDF to `D:\INTERNSHIP`, highlighting $1.3M savings by retaining 260 customers.

## Setup
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
4. **requirements.txt**:
```text
pandas
scikit-learn
python-pptx
matplotlib
comtypes
jupyter

Note: Obtain `data_for_predictions.csv` from your data source. Expected columns include `id`, `churn`, and features (e.g., contract length, consumption).
jupyter notebook churn_prediction.ipynb

python generate_executive_summary.py


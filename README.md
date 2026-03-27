# DSAI4103_CourseProject
## Marketing and E-Commerce Purchase Prediction

A machine learning project for analyzing customer behavior and predicting purchase events in e-commerce data.

### Project Overview
This project uses a multi-file marketing and e-commerce dataset to study customer behavior, build predictive models, explain model predictions using SHAP, and prepare data for dashboard reporting.

### Dataset
Original dataset: https://www.kaggle.com/datasets/geethasagarbonthu/marketing-and-e-commerce-analytics-dataset?resource=download

The project uses the following files:
- customers.csv
- products.csv
- campaigns.csv
- transactions.csv
- events.csv

Note: The dashboard dataset can be generated directly from the notebook by exporting **dashboard_data.csv**.

### Dashboard
Dashboard link: https://app.powerbi.com/groups/me/reports/db3ba549-449d-4fee-80bd-869518b58d4e/5163d4b42eefc15dd1d6?experience=power-bi
Note: The dashboard file is not stored in this repository because of its large file size.

### Repository Structure
- **DSAI4103_CourseProject_60302049.ipynb**: main project notebook
- **data/**: dataset files
- **Dashboard/**: Power BI dashboard Screenshots

Note: The full dataset is available from the original source link above. Some large files cannot be included directly in this repository due to file size limits.

### Final Model
The final selected model was a tuned Logistic Regression model, chosen because it provided the most practical balance between detecting purchase events and reducing false positives.

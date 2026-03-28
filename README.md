# DSAI4103_CourseProject
## Marketing and E-Commerce Purchase Prediction

A machine learning project for analyzing customer behavior and predicting purchase events in e-commerce data.

### Project Overview
This project uses a multi-file marketing and e-commerce dataset to study customer behavior, build predictive models, explain model predictions using SHAP, and prepare data for dashboard reporting.

Google Colab Link: https://colab.research.google.com/drive/1WCqBlj1N8-QFnCIi5lfDXEb-2wPe48lE?usp=sharing

### Dataset
Original Dataset Link: https://www.kaggle.com/datasets/geethasagarbonthu/marketing-and-e-commerce-analytics-dataset?resource=download

The project uses the following files:
- customers.csv
- products.csv
- campaigns.csv
- transactions.csv
- events.csv

Note: The dashboard dataset can be generated directly from the notebook by exporting **dashboard_data.csv**.

### Dashboard
Dashboard Link: https://app.powerbi.com/links/9TBtp98DxX?ctid=b30f4b44-46c6-4070-9997-f87b38d4771c&pbi_source=linkShare

Note: The dashboard file is not stored in this repository because of its large file size.

### Repository Structure
- **DSAI4103_CourseProject_60302049.ipynb**: main project notebook
- **DSAI4103_Presentation**: presentation slides
- **data/**: dataset files
- **Dashboard/**: Power BI dashboard Screenshots

Note: The full dataset is available from the original source link above. Some large files cannot be included directly in this repository due to file size limits.

### Final Model
The final selected model was a tuned Logistic Regression model, chosen because it provided the most practical balance between detecting purchase events and reducing false positives.

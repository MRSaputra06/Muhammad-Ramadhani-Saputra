# Muhammad-Ramadhani-Saputra
UAS DATA SCIENCE
"A Data Science project analyzing social media addiction among students" using Python in Google Colab. The project covers EDA, data preprocessing, and modeling with a Random Forest classifier.
>Overview
This project examines the level of social media addiction among students. Through exploratory data analysis (EDA), preprocessing, and building a Random Forest model, it identifies key factors contributing to addictive behaviors and evaluates model performance.
>Motivation
Social media addiction can negatively impact students' academic performance and mental health. This study aims to:
- Quantify addiction levels among students.
- Identify key predictors (e.g., usage time, platform preferences).
- Provide insights for educators and mental health professionals.
>Dataset
- Source: [insert link or dataset file]
- Features: e.g., age, daily_usage_hours, addiction_score, platform_type, gender.
- Preprocessing steps:
  - Handling missing values (mean/mode imputation)
  - Encoding categorical variables (One-Hot / Label Encoding)
  - Scaling numeric features (MinMaxScaler or StandardScaler)
>Methodology
1. Exploratory Data Analysis (EDA)
   - Descriptive statistics, correlation analysis, and feature distributions.
   - Visualizations using `Matplotlib` & `Seaborn`.
2. Data Preprocessing
   - Imputation, encoding, scaling.
   - Train-test split (e.g., 80:20 stratified).
3. Modeling
   - Trained `RandomForestClassifier` from scikit‑learn.
   - Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
   - Identified feature importance to highlight key predictors.
>Results & Evaluation
- Model performance: Accuracy = XX%, F1-score = YY.
- Top features: daily_usage_hours, `platform_type, age.
- Visual aids:
  - Score distributions
  - Correlation heatmap
  - Confusion matrix
  - Feature importance bar chart

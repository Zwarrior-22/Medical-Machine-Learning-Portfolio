Healthcare Machine Learning Portfolio
This repository contains end-to-end machine learning pipelines for clinical diagnostics. Each project focuses on a different aspect of medical data science, from robust data imputation to high-precision classification and clinical threshold optimization.
🚀 Projects Overview
1. Heart Disease Classification (01_Heart_Disease)
Objective: Predict the presence of cardiovascular disease based on clinical markers (age, cholesterol, chest pain type).
Key Techniques: Feature Engineering, Random Forest Classification, and Feature Importance Ranking.
Clinical Insight: Identifies key risk factors like ca (vessels colored by fluoroscopy) and oldpeak (ST depression) to assist in non-invasive screening.
2. Market Pulse: Diabetes Risk Prediction (02_Diabetes_Pulse)
Objective: Stratify diabetes risk using metabolic markers like Glucose, BMI, and Insulin levels.
Key Techniques: Logistic Regression, Median Imputation (handling biologically impossible zeros), and GridSearchCV for hyperparameter tuning.
Clinical Insight: Prioritizes model interpretability through Logistic Regression coefficients, allowing clinicians to understand the "why" behind each risk score.
3. Breast Cancer Diagnostic Model (03_Breast_Cancer)
Objective: Classify breast mass as Malignant (1) or Benign (0) using digitized cell nuclei measurements.
Key Techniques: Support Vector Machines (SVM), XGBoost, and Manual Threshold Shifting.
Clinical Insight: Optimized for 99% Recall by shifting the decision threshold to 0.40, ensuring that the model minimizes False Negatives—the most dangerous error in cancer diagnostics.
🛠️ Technical Skill Set
Data Science: Exploratory Data Analysis (EDA), Correlation Analysis, Outlier Detection.
Preprocessing: $StandardScaler$, Label Encoding, Handling Multicollinearity.
ML Algorithms: SVM, Random Forest, XGBoost, Logistic Regression.
Evaluation Metrics: Precision-Recall Trade-offs, F1-Score, AUC-ROC, Confusion Matrix.


📂 Repository Structure
├── 01_Heart_Disease/       # Feature Engineering & Random Forest
├── 02_Diabetes_Pulse/      # Imputation & Logistic Regression
└── 03_Breast_Cancer/       # SVM & Recall Optimization


✍️ Author
Nitin Ishan
https://www.linkedin.com/in/nitin-lshan/


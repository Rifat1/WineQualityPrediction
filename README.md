### Wine Quality Prediction using Logistic Regression and Feature Engineering

**Objective:**  
To predict wine quality scores based on physicochemical properties using a classification model, while addressing class imbalance and experimenting with feature selection and scaling techniques.

**Technologies Used:**  
Python, pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn (SMOTE)

**My Role and Contributions:**

- Conducted exploratory data analysis (EDA) to understand distributions, correlations, and outliers.
- Implemented Logistic Regression to model wine quality classification (target values 3–8).
- Addressed severe class imbalance using **SMOTE** oversampling.
- Evaluated the effect of different scaling techniques (**MinMaxScaler**, **RobustScaler**, **StandardScaler**) and feature subsets (using correlation heatmaps).
- Compared model performance across scaling and feature combinations using accuracy metrics.

**Outcomes:**

- Achieved a **20% improvement in model accuracy** using **RobustScaler** compared to baseline (no scaling).
- Identified key predictors including `alcohol`, `citric acid`, and `free sulfur dioxide` for high-quality wine.
- Developed a fully reproducible ML pipeline from **EDA to evaluation**.

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
<img width="2006" height="1005" alt="output1" src="https://github.com/user-attachments/assets/666344d4-21d5-4809-a789-e7cc98e52547" />
<img width="2004" height="1006" alt="output2" src="https://github.com/user-attachments/assets/8daaf74d-bcd5-4c02-a3f4-ede141532d8f" />
<img width="2006" height="1005" alt="output3" src="https://github.com/user-attachments/assets/c467aedc-259b-4984-a4e1-3328d97f8c50" />
<img width="1559" height="935" alt="output5" src="https://github.com/user-attachments/assets/c76d42a6-ebd1-4cf2-a283-4abe7c5fe369" />
<img width="580" height="432" alt="output4" src="https://github.com/user-attachments/assets/eb747fcc-d4e0-4193-a5b5-67fe824c39b5" />

# Breast Cancer Tumor Classification Using Machine Learning

This project applies machine learning techniques to classify breast cancer tumors as **malignant** or **benign** based on the Breast Cancer dataset. The workflow demonstrates a complete end-to-end data science pipeline.

## Project Overview

The main steps performed in this project include:

1. **Data Preprocessing**  
   - Handling missing values and cleaning the dataset.
   - Encoding categorical features using One-Hot Encoding.

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing class distribution.
   - Understanding feature correlations and distributions.

3. **Feature Scaling and Selection**  
   - Scaling features with StandardScaler.
   - Selecting the most important features using Chi-Squared test.

4. **Model Training and Evaluation**  
   - Training models such as Random Forest, Logistic Regression, and SVM.
   - Evaluating model performance using accuracy, classification reports, and confusion matrices.

5. **Model Comparison**  
   - Comparing different models based on test set accuracy to identify the best-performing model.

6. **Feature Impact Analysis**  
   - Analyzing feature importance using Random Forest to understand which features have the largest effect on predictions.

7. **Conclusion and Key Insights**  
   - Summarizing findings and model performance.
   - Highlighting the most important features for tumor classification.

## Dataset

- Source: [Breast Cancer dataset](https://raw.githubusercontent.com/datasets/breast-cancer/refs/heads/main/data/breast-cancer.csv)  
- Contains nucleus-level geometric and texture features of tumors.

## Tools and Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

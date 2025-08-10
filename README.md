# Fraud Detection – Machine Learning Project

##  Project Overview
This project focuses on detecting fraudulent transactions using supervised machine learning techniques.  
Initially, a **Linear Regression** approach was explored as a baseline model to predict transaction outcomes.  
However, during data exploration, it became clear that the dataset was **highly imbalanced** (fraud cases represented only a small percentage of total transactions).  
This imbalance caused the regression model to perform poorly in detecting actual fraud cases, prompting a shift to **Random Forest Classification**.

##  Goals
- Identify fraudulent transactions while minimizing false positives.
- Compare baseline model performance with a more robust classifier.
- Handle imbalanced data to improve recall on fraud cases.

##  Tools & Libraries
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Machine Learning Models**: Linear Regression (baseline), Random Forest Classifier
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, ROC-AUC

##  Workflow
1. **Data Loading & Cleaning**
   - Handled missing values and outliers.
   - Converted categorical features to numeric.
2. **Exploratory Data Analysis (EDA)**
   - Distribution of transaction types and amounts.
   - Correlation heatmaps for feature relationships.
3. **Baseline Model – Linear Regression**
   - Tested as a simple starting point.
   - Poor fraud detection performance due to class imbalance.
4. **Handling Imbalance**
   - Applied class weighting and resampling techniques (e.g., SMOTE/undersampling).
5. **Final Model – Random Forest Classifier**
   - Significantly improved recall and precision on minority fraud cases.
   - Achieved balanced performance across evaluation metrics.
6. **Model Evaluation**
   - Compared both models using precision, recall, F1-score, and ROC curves.

##  Key Insights
- Fraudulent transactions accounted for less than X% of the dataset, requiring targeted model adjustments.
- Random Forest outperformed the baseline regression approach in detecting fraud cases.
- Handling class imbalance is critical in real-world fraud detection scenarios.

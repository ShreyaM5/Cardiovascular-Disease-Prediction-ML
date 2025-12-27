# CardioCare-Cardiovascular-Disease-Prediction-ML
🫀 Predicting cardiovascular disease risk using multiple supervised machine learning models.

# 📌 Project Overview
Cardiovascular diseases (CVDs) are one of the leading causes of death worldwide.  
This project uses patient health data to build and compare multiple supervised learning models to predict the risk of cardiovascular disease.  
The aim is to identify the most effective model for reliable and interpretable predictions.


# 📊 Dataset
- **Source:** [UCI Heart Disease Dataset]
- **Features:** Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, ST depression, slope, number of major vessels
- **Target:** Presence (1) or absence (0) of cardiovascular disease

# ⚙️ Methodology
1. **Data preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features
2. **Outlier detection** (to improve data quality)
3. **Class balancing**
   - **SMOTE** (Synthetic Minority Over-sampling Technique)
   - **ADASYN** (Adaptive Synthetic Sampling)
4. **Model training & evaluation**  

# 🤖 Models Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naïve Bayes  
- Decision Tree Classifier  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- LightGBM  
- Artificial Neural Network (ANN)

- ## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC 

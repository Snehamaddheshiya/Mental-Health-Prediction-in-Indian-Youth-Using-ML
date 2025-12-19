# Mental Health Analysis Among Indian Youth (Machine Learning Project)

This repository contains my data science minor project on analyzing mental health, stress, anxiety, and depression among Indian youth using machine learning.

## 🔍 Project Overview

- Dataset: 600 survey responses from Indian students and young professionals  
- Goal:  
  - Understand stress and mental health patterns  
  - Predict stress levels and mental health risk  
  - Identify high-stress students who may need support  

## 📂 Files

- `collecteddata.csv` – Original survey dataset  
- `mental_health_analysis.ipynb` – Main Jupyter Notebook with:
  - Data loading and exploration  
  - Data cleaning and preprocessing  
  - Outlier detection and removal  
  - Feature engineering  
  - Machine learning modeling (5 insights)  
  - Result summaries and visualizations  
- `report/Mental_Health_Analysis_Report.pdf` – Full project report (30+ pages)

## 🧠 Main Analyses (Insights)

1. **Predicting Student Stress Levels**  
   - Regression models to predict stress (1–5) from lifestyle and demographic features  
   - Best model: Linear Regression (MAE ≈ 0.79)

2. **Identifying Mental Health Risk (Anxiety/Depression)**  
   - Binary classification (has mental issue vs no issue)  
   - Best model: Logistic Regression (Accuracy ≈ 66%, good recall for screening)

3. **Classifying Emotional States**  
   - Multi-class classification (Happy, Neutral, Stressed, Anxious, Depressed)  
   - Best model: Random Forest (slightly better than random, emotional state is complex)

4. **Impact of Sleep on Stress**  
   - Regression models using sleep hours, screen time, exercise, age group  
   - Confirms that lifestyle alone cannot fully explain stress, but sleep still matters

5. **Detecting High-Stress Students (Levels 4–5)**  
   - Binary classification (high stress vs low/medium stress)  
   - Best model: SVM (Accuracy ≈ 66%, good recall for high-stress cases)

## 📊 Technologies

- Python, Jupyter Notebook  
- pandas, NumPy  
- matplotlib, seaborn  
- scikit-learn (Linear Regression, Logistic Regression, Decision Trees, Random Forest, SVM, Naive Bayes, KNN)




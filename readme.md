# 🛢️ Kaggle Oil & Gas Fields Classification (Top 1 & 2 Solution)

## 🏆 About this Project
This repository contains my **Kaggle Top 1 & 2 winning solutions** for the competition **[Classification of Oil and Gas Fields](https://www.kaggle.com/competitions/classification-of-oil-and-gas-fields/overview)**.

- 🎯 **Task**: Binary classification – predict whether an oil & gas field is **Onshore (0)** or **Offshore (1)**.
- 📊 **Metric**: F1-score
- 🥇 **Leaderboard Results**:  
  - **Public LB**: `0.95908` (#1) | `0.93725` (#2)  
  - **Private LB**: `0.94267` (#1) | `0.91539` (#2)

## 📂 Repository Structure
├── data/ # Dataset (train.csv, test.csv, etc.)
├── submission_machine_learning_in_oil.qmd # Quarto notebook (R + Python)
├── README.md # This file


## ⚙️ Methods
1. **Data Preprocessing**
   - Cleaning missing values
   - Handling class imbalance
   - Feature selection via importance scores

2. **Machine Learning Models**
   - Random Forest
   - XGBoost
   - LightGBM
   - CatBoost
   - Gradient Boosting

3. **Evaluation**
   - 5-fold Stratified Cross Validation
   - Metric: **F1-score**

4. **GIS-based Hybrid Solution**
   - Onshore/Offshore classification using **geographic distance thresholds**
   - Noise-enhanced methods (v13, v14)

## 📈 Results
- Generated multiple submission files (e.g., `submission_gis_v13_hybrid_noise.csv`, `submission_gis_v14_noise_enhanced.csv`)
- Combined Machine Learning + GIS approaches achieved **Top 1 and 2** on both Public and Private Leaderboards.

🙌 Acknowledgements
Kaggle community & competition organizers

Teammates and collaborators

Libraries: scikit-learn, imbalanced-learn, pandas, xgboost, lightgbm, catboost, seaborn, matplotlib


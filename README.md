# 🐨 Koala Conservation Predictive Modeling

## 📊 Overview
This project explores how environmental and biological factors influence the physical characteristics of koalas. Using real-world measurement data, we perform statistical hypothesis testing and regression modeling to derive insights useful for conservation strategy and habitat planning.

## 🛠️ Tools & Libraries Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Linear Regression)
- Statistical Tests (One-sample and Independent T-Test)
- Correlation & Heatmaps

## 📁 Dataset Summary
- Physical features: Head Length, Skull Width, Ear Size, Chest Circumference, Foot Length
- Environmental info: Habitat Region (encoded)
- Gender Classification

## 🧪 Key Steps & Analysis

1. **Data Cleaning**:
   - Removed missing values, handled outliers
   - Standardized formatting for analysis

2. **Exploratory Visualization**:
   - Boxplots to explore gender-wise trait variation
   - Scatter plots for total length vs head length

3. **Hypothesis Testing**:
   - Tested if average head length differs from a reference value (92.0 mm)
   - Compared male vs female head lengths using independent t-tests

4. **Regression Models**:
   - Simple Linear Regression: Predict total length using head length (R² ≈ 0.39)
   - Multiple Linear Regression: Used head length, skull width, and foot length (R² ≈ 0.51)

5. **Correlation Analysis**:
   - Habitat strongly correlated with ear size (0.88) and foot length (0.79)
   - Paw size showed negative correlation with habitat (-0.46)

## 📈 Sample Visualizations
- Head Length vs Total Length Regres

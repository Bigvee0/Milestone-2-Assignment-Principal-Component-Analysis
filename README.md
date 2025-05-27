# Milestone-2-Assignment-Principal-Component-Analysis
# Cancer Dataset PCA Analysis - Anderson Cancer Center

## Donor Funding Model Development Project

### 📋 Project Overview
This project implements Principal Component Analysis (PCA) on the breast cancer dataset from sklearn to identify essential variables for securing donor funding at the Anderson Cancer Center. The analysis reduces dimensionality from 30 features to 2 principal components while maintaining predictive capability through logistic regression.

### 🎯 Project Objectives
1. **PCA Implementation**: Demonstrate essential variable extraction from cancer dataset  
2. **Dimensionality Reduction**: Reduce dataset to 2 PCA components  
3. **Bonus Task**: Implement logistic regression for prediction  
4. **Insights Generation**: Provide actionable insights for donor funding proposals  

### 📊 Dataset Information
- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Samples**: 569 cancer cases
- **Features**: 30 numerical features (mean, standard error, worst values)
- **Target**: Binary classification (Malignant: 0, Benign: 1)
- **Feature Categories**:  
  - Radius, Texture, Perimeter, Area, Smoothness  
  - Compactness, Concavity, Concave points, Symmetry, Fractal dimension  

### 🛠️ Requirements

#### Python Version
- Python 3.7 or higher

#### Required Libraries
```bash
pip install numpy pandas matplotlib seaborn scikit-learn

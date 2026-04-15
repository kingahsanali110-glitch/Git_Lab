Machine Learning with Scikit-Learn Labs

A comprehensive collection of hands-on lab notebooks for learning Machine Learning fundamentals using Python and Scikit-Learn.

---

## 📚 Course Overview

This repository contains three progressive lab sessions covering essential ML concepts:

| Session | Topic | Duration | Key Concepts |
|---------|-------|----------|--------------|
| Lab 1 | Data Preprocessing | 60-75 min | Missing values, Encoding, Scaling, Outliers |
| Lab 2 | Classification Models I | 60-75 min | Logistic Regression, KNN |
| Lab 3 | Classification Models II | 60-75 min | Decision Trees, Random Forests |

---

## 🗂️ Lab Notebooks

### 📊 Lab 1: Data Preprocessing
**File:** `Week5_Lab1_Data_Preprocessing.ipynb`

Learn essential data preparation techniques before model training:

- **Missing Value Handling**
  - Detection and visualization
  - Imputation strategies (mean, median, mode)
  - Using `SimpleImputer`

- **Categorical Encoding**
  - Label Encoding for ordinal data
  - One-Hot Encoding for nominal data
  - `pandas.get_dummies()` vs `OneHotEncoder`

- **Feature Scaling**
  - StandardScaler (Z-score normalization)
  - MinMaxScaler (0-1 normalization)
  - When to use which scaler

- **Outlier Detection**
  - IQR (Interquartile Range) method
  - Z-score method
  - Visualization techniques

- **Complete Preprocessing Pipeline**
  - `ColumnTransformer` for mixed data types
  - Building reusable pipelines

**Dataset:** Ride-sharing service data (Uber/Careem-like)

---

### 🎯 Lab 2: Classification Models I - Logistic Regression & KNN
**File:** `Week5_Lab2_Classification_LogReg_KNN.ipynb`

Master two fundamental classification algorithms:

- **Logistic Regression**
  - Sigmoid function visualization
  - Probability predictions
  - Feature importance via coefficients
  - Model interpretation

- **K-Nearest Neighbors (KNN)**
  - Distance-based classification
  - Finding optimal K value
  - Effect of feature scaling
  - Distance metrics (Euclidean, Manhattan)

- **Model Evaluation**
  - Confusion matrix interpretation
  - Accuracy, Precision, Recall, F1-Score
  - Model comparison techniques

**Dataset:** Bank Customer Subscription (Term Deposit Marketing)

---

### 🌲 Lab 3: Classification Models II - Decision Trees & Random Forests
**File:** `Week5_Lab3_DecisionTrees_RandomForests.ipynb`

Explore tree-based ensemble methods:

- **Decision Trees**
  - Tree visualization with `plot_tree`
  - Understanding splits and nodes
  - Controlling tree depth
  - Overfitting prevention

- **Random Forests**
  - Ensemble learning concept
  - Bagging and feature randomness
  - Number of estimators

- **Advanced Topics**
  - Feature importance analysis
  - Hyperparameter tuning with `GridSearchCV`
  - Cross-validation strategies

**Dataset:** Wine Quality Classification (Multi-class)

---

## 🛠️ Requirements

```bash
# Core Libraries
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0

# Machine Learning
scikit-learn>=1.0.0
```

### Quick Install
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🚀 Getting Started

### Option 1: Google Colab (Recommended)
1. Upload notebooks to Google Drive
2. Open with Google Colab
3. Run cells sequentially

### Option 2: Local Jupyter
```bash
# Clone or download the repository
# Navigate to the folder
jupyter notebook
```

### Option 3: VS Code
1. Install Python extension
2. Install Jupyter extension
3. Open `.ipynb` files directly

---

## 📖 How to Use These Labs

1. **Read the markdown cells** - They contain important concepts and explanations
2. **Run code cells sequentially** - Each cell builds on the previous
3. **Experiment!** - Modify parameters and observe changes
4. **Complete practice exercises** - Found at the end of each lab
5. **Check your understanding** - Answer the review questions

---

## 🎯 Learning Outcomes

By completing these labs, you will be able to:

✅ Clean and preprocess real-world datasets  
✅ Handle missing values using various imputation strategies  
✅ Encode categorical variables appropriately  
✅ Scale features for optimal model performance  
✅ Build and evaluate Logistic Regression models  
✅ Implement and tune KNN classifiers  
✅ Create and visualize Decision Trees  
✅ Build Random Forest ensembles  
✅ Perform hyperparameter tuning with GridSearchCV  
✅ Compare and select the best model for a given problem  

---

## 📁 Repository Structure

```
Week5-ML-Scikit-Learn-Labs/
│
├── README.md
├── Week5_Lab1_Data_Preprocessing.ipynb
├── Week5_Lab2_Classification_LogReg_KNN.ipynb
└── Week5_Lab3_DecisionTrees_RandomForests.ipynb
```

---

## 💡 Tips for Success

| Do's ✅ | Don'ts ❌ |
|---------|----------|
| Run cells in order | Skip cells randomly |
| Read error messages carefully | Ignore warnings |
| Experiment with parameters | Just copy-paste code |
| Take notes on key concepts | Rush through without understanding |
| Complete practice exercises | Skip the exercises |

---

## 🔗 Additional Resources

- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

---

## 📝 License

This material is created for educational purposes. Feel free to use and modify for your learning journey.

---

## 🤝 Contributing

Found an issue or have a suggestion? Feel free to:
- Open an issue
- Submit a pull request
- Contact the instructor

---

**Happy Learning! 🚀**

*"The best way to learn ML is by doing ML"*

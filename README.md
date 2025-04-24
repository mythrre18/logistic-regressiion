Breast Cancer prediction using logistic regression:
This research uses the **Breast Cancer Wisconsin Diagnostic Dataset** to predict if a tumour is **benign** or **malignant** using a variety of machine learning methods.  It consists of **cross-validation**, **hyperparameter tuning**, **data preprocessing**, and **model evaluation** using a range of performance measures.
 Models Employed
 1)Support Vector Machine (SVM)
 2)Decision Tree Classifier
 3)Random Forest Classifier
 4)Naive Bayes
 5)Logistic Regression** (both with and without cross-validation)

 Strategies Used

 Target variable label encoding; Standard Scaling of features; Stratified Train-Test Split to preserve class distribution; GridSearchCV for hyperparameter tuning; Confusion Matrix Visualisation (Seaborn heatmaps); Feature Importance Analysis for tree-based models

Key Libraries:
pandas, numpy
matplotlib, seaborn
scikit-learn

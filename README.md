# Support Vector Machine (SVM) - Breast Cancer Classification

This project demonstrates how to apply Support Vector Machines (SVM) for binary classification using a real-world breast cancer dataset.

## Tools & Libraries
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib

## Objectives
- Train SVM with linear and RBF kernels
- Visualize decision boundaries using PCA
- Tune hyperparameters (`C`, `gamma`) using GridSearchCV
- Evaluate performance using cross-validation

##  Dataset
A `breast-cancer.csv` file is used with binary target labels. Any categorical features are label-encoded. If the target is continuous, it is binarized using median thresholding.

## How to Run
1. Place `breast-cancer.csv` in your notebook directory
2. Run the Jupyter Notebook
3. Check model performance reports and decision boundary plots

## Output
- Classification reports (precision, recall, F1-score)
- 2D decision boundary plot (PCA-reduced)
- Best hyperparameters from GridSearchCV
- 5-fold cross-validation accuracy



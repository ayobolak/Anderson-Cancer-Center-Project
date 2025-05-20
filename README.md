# PCA on Breast Cancer Dataset - Anderson Cancer Center Project

##  Project Overview
This project uses Principal Component Analysis (PCA) to reduce dimensionality and identify the most important variables in the breast cancer dataset. The outcome will support donor funding analysis by simplifying complex data into key components.

##  Tasks Completed
- Loaded and standardized the breast cancer dataset from `sklearn.datasets`
- Applied PCA to reduce features to 2 main components
- Visualized the PCA result
- (Bonus) Implemented logistic regression on the PCA-reduced dataset

##  How to Run
1. Clone this repo or unzip the downloaded file.
2. Open the Jupyter notebook: `pca_breast_cancer.ipynb`
3. Run all cells to see PCA analysis and optional logistic regression.

## Dependencies
- numpy
- pandas
- matplotlib
- scikit-learn

## Results
- PCA reduced the dataset to 2 components with ~63% total variance explained.
- Logistic Regression Accuracy: ~93% on test data.



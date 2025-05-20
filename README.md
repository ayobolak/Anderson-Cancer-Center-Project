
## Key Tasks Completed

### 1. Load and Explore the Dataset
- Used `load_breast_cancer()` from `sklearn.datasets`
- Converted the dataset into a pandas DataFrame for easy manipulation

### 2. Standardize the Data
- Applied `StandardScaler` to normalize all features
- Standardization is critical for PCA to function correctly

### 3. Perform PCA
- Applied PCA to reduce the dataset from 30 features to 2 principal components
- Extracted and printed the **explained variance ratio** of the components
- Visualized the two PCA components using a scatter plot, colored by cancer diagnosis

 
  ![image](https://github.com/user-attachments/assets/fb5c6c83-d541-4782-9b48-7dfef0ea9dc9) 

### 4. Logistic Regression
- Trained a logistic regression model using only the 2 PCA components
- Split the data into training and testing sets (80/20)
- Evaluated the model using **accuracy**, **confusion matrix**, and **classification report**

---

## Results

- **Explained Variance by 2 PCA Components**: ~63% total variance
- **Logistic Regression Accuracy**: ~93%
- **Insights**: The two PCA components retain a meaningful amount of the original data's variance and are effective for classification

---

## How to Run This Project

### Option 1: Using Jupyter Notebook
1. Make sure you have Python 3.x installed
2. Install required packages (see below)
3. Open and run `pca_breast_cancer.ipynb` in Jupyter Notebook or JupyterLab

## Dependencies
- numpy
- pandas
- matplotlib
- scikit-learn



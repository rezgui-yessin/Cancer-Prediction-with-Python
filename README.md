In supervised machine learning, the dataset is divided into two main parts:

### 🔹 Target Variable (y)
- The **target** is the value we want the model to predict.
- In this dataset, the target is the **`diagnosis`** column.
- It represents the class of the tumor (e.g. *Malignant* or *Benign*).

### 🔹 Predictor Variables (X)
- The **predictors** (also called features) are the input variables used to make predictions.
- All columns **except `diagnosis`** are considered predictors.
- These features describe the characteristics of the tumor (size, texture, smoothness, etc.).

### 🔹 How we identify them
- The target column is chosen based on the **problem objective**: predicting cancer diagnosis.
- Predictor columns are the remaining variables that help explain or predict the target.

### 🔹 Why this separation is important
- Machine learning models learn a relationship between **X (predictors)** and **y (target)**.
- Keeping them separate ensures correct training, testing, and evaluation of the model.
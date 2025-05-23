# adult-income-prediction
## Supervised Machine Learning – Adult Income Dataset

## 📊 Project Overview

This project focuses on applying supervised machine learning techniques to the **Adult Income Dataset** to predict whether a person earns more than \$50K per year based on census data. The main tasks include data preprocessing, model training using Logistic Regression, Decision Tree, and Random Forest, and evaluating each model using standard metrics.

## 📁 Dataset

- **Source**: [UCI Adult Income Dataset](https://archive.ics.uci.edu/dataset/2/adult)
- **Files used**:
  - `adult.data` – Training data
  - `adult.test` – Testing data (Note: the first line is ignored as it is not data)

## 🧪 Steps Performed

### ✅ Data Preprocessing
- Handled missing values:
  - **Numerical columns**: Imputed using mean.
  - **Categorical columns**: Imputed using mode.
- Encoded categorical variables using **one-hot encoding**.
- Scaled numerical features using **StandardScaler**.
- Applied preprocessing pipelines using `ColumnTransformer`.

### ✅ Model Training & Evaluation
Trained the following models:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

Each model was evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

## 📦 Requirements

To run the code, install the following Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn

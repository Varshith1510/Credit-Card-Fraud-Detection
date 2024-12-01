# Credit Card Fraud Detection

## Objective

The goal of this project is to detect fraudulent credit card transactions based on transaction data. The primary aim is to build a model that can accurately classify whether a transaction is fraudulent or not, using various machine learning algorithms.

---

## Dataset

The dataset used for this project is available on Kaggle:  
[Kaggle Dataset Link](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

---

## Steps Taken

### 1. Data Preprocessing
- **Removing Unnecessary Columns:** Removed columns with low correlation to the target variable to reduce noise and improve model efficiency.
- **Class Imbalance Handling:** Addressed the class imbalance by ensuring an equal number of samples from both the fraudulent and non-fraudulent classes. This was achieved through undersampling the majority class.

### 2. Feature Engineering
- **Label Encoding:** Applied label encoding to convert categorical features into numeric form, enabling the use of machine learning algorithms.

### 3. Model Building
- **Logistic Regression:** Initially trained a Logistic Regression model as a baseline.
- **Decision Tree Classifier:** Trained a Decision Tree model to see if it could improve classification performance.
- **Random Forest Classifier:** Trained a Random Forest model to capture more complex patterns in the data.

### 4. Model Evaluation
- **Overfitting Issue:** Both the Decision Tree and Random Forest models showed signs of overfitting, where they performed well on the training data but poorly on unseen data.
- **Final Model Selection:** Based on the evaluation, Logistic Regression was chosen as the final model due to its generalization capabilities and stable performance across both training and test data.

---

## Kaggle Notebook

You can find the complete code implementation and analysis in my Kaggle notebook:  
[Kaggle Notebook Link](https://www.kaggle.com/code/varshithpsingh/credit-card-fraud-detection)

---

## Insights and Results

- **Feature Reduction:** Removing unnecessary features improved the model's performance by reducing overfitting and computational complexity.
- **Class Imbalance Handling:** Addressing the class imbalance led to more reliable predictions of fraudulent transactions.
- **Model Performance:** Logistic Regression outperformed Decision Tree and Random Forest models in terms of generalization, making it the best choice for final predictions.

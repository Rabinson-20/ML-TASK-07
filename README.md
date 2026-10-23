# Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview
Credit Card Fraud Detection is a Machine Learning project that identifies potentially fraudulent credit card transactions using a **Random Forest Classifier**. The model analyzes transaction data, predicts fraudulent activities, and evaluates its performance using various classification metrics.

## 🎯 Objectives
- Analyze credit card transaction data.
- Identify fraudulent and genuine transactions.
- Train a machine learning classification model.
- Evaluate model performance using classification metrics.
- Visualize the confusion matrix, ROC curve, and feature importance.
- Identify detected and missed fraudulent transactions.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📂 Dataset
The project uses a credit card transaction dataset named `creditcard.csv`.

The target column is `Class`:
- `0` – Genuine transaction
- `1` – Fraudulent transaction

**Note:** The dataset is not included in this repository. You must obtain the dataset separately and update the file path in the notebook if necessary.

## ⚙️ Project Workflow

1. **Data Loading:** Load the dataset using Pandas.
2. **Data Exploration:** Examine the dataset structure, data types, missing values, and class distribution.
3. **Data Preparation:** Separate the input features and target variable.
4. **Data Splitting:** Split the dataset into 80% training data and 20% testing data.
5. **Model Training:** Train a Random Forest Classifier with 100 estimators.
6. **Prediction:** Predict whether transactions are genuine or fraudulent.
7. **Model Evaluation:** Calculate precision, recall, F1-score, ROC-AUC, and the classification report.
8. **Fraud Analysis:** Identify detected and missed fraudulent transactions.
9. **Feature Importance:** Visualize the ten most important features.
10. **Visualization:** Display the confusion matrix and ROC curve.

## 🤖 Machine Learning Algorithm
**Random Forest Classifier**

The model uses the following configuration:
- Number of estimators: 100
- Class weighting: `balanced_subsample`
- Random state: 42
- Test size: 20%
- Parallel processing: `n_jobs=-1`

## 📊 Evaluation Metrics

The model is evaluated using the following metrics:

- **Precision:** Measures how many transactions predicted as fraudulent are actually fraudulent.
- **Recall:** Measures how many actual fraudulent transactions are correctly detected.
- **F1-Score:** Balances precision and recall.
- **ROC-AUC:** Measures the model's ability to distinguish between genuine and fraudulent transactions.
- **Confusion Matrix:** Shows correct and incorrect classifications.

## 📈 Project Outputs
After running the notebook, the project generates:

- Confusion matrix visualization.
- Classification report and evaluation metrics.
- Fraud detection and missed fraud counts.
- Top 10 feature importance visualization.
- ROC curve visualization.
- `actual_fraudulent_test_transactions.csv` containing actual fraudulent transactions from the test dataset.

## 🔮 Future Enhancements
- Compare Random Forest with other machine learning algorithms.
- Perform hyperparameter tuning to improve performance.
- Use cross-validation for more reliable evaluation.
- Optimize prediction thresholds to balance fraud detection and false alarms.
- Develop a simple web application for real-time fraud prediction.

## ⚠️ Limitations
- Fraudulent transactions are typically much less common than genuine transactions.
- Accuracy alone may not provide a reliable measure of fraud detection performance.
- Model performance depends on the dataset and selected features.
- This project is intended for educational purposes and is not a production-ready fraud prevention system.

## 👨‍💻 Author
**Samrabinson P**

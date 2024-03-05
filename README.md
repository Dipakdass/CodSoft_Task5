
# Credit Card Fraud Detection Project
This project aims to develop a machine learning model for detecting credit card fraud. With the increasing reliance on electronic transactions, credit card fraud has become a significant concern for both financial institutions and consumers. The goal is to build a robust model that can accurately classify transactions as either legitimate or fraudulent.


## Dataset
The dataset used for this project is sourced from Kaggle and contains transactions made by credit cards in September 2013 by European cardholders. It consists of numerical input variables, which are the result of a PCA transformation due to confidentiality reasons. The features include 'Time', 'Amount', and anonymized features labeled as 'V1' through 'V28'. The target variable, 'Class', indicates whether a transaction is fraudulent (1) or legitimate (0).
## Methodology
1. Data Preprocessing: Performed standard preprocessing steps including checking missing values, scaling numerical feature i.e Amount, deals with duplicated rows.
2. Feature Engineering: To address class imbalance, we employed techniques such as oversampling the minority class using Synthetic Minority Over-sampling Technique (SMOTE).
3. Model Selection: Experimented with multiple algorithms including Logistic Regression,  KNeighborsClassifier and Randomforest Classifier.
4. Model Evaluation: The selected model will be evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.
6. Save Model/Deployment: The final model saved as a pickle file to use for the prediction purpose.
## Requirements
1. Python 3.x
2. Jupyter Notebook/ Google Colab
3. Pandas
4. NumPy
5. Scikit-learn
6. Matplotlib
7. Seaborn
8. Pickle
## Usage
1. Clone this repository.
2. Install the required dependencies using pip install -r requirements.txt.
3. Open the Jupyter Notebook credit_card_fraud_detection.ipynb.
4. Follow the step-by-step instructions provided in the notebook for data preprocessing, model training, evaluation, and deployment.
## Contributor
Dipak Das


## License
This project is licensed under CodSoft.

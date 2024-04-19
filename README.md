![image](https://github.com/aakashr21/Fraud-Transaction-Detection/assets/88080322/9650e701-d5ae-492a-b651-0b98f28841a3)

# Fraud Transaction Detection
## Description
This model aims to detect online fraud payment transaction usinf classification algorithm.
## Tools Used
## Import libraries for data wrangling
numpy, pandas

## Import libraries for data visualisation
matplotlib.pyplot, seaborn

## Import libraries for model building
Logistic regression, RandomForestClassifier, SMOTE, accuracy_score, precision_score, recall_score, f1_score,roc_auc_score, confusion_matrix, ConfusionMatrixDisplay

     
## Insights
## All the analysis
* Most number of transaction are of cash out type, followed by payment, cash in, transfer and debit types.
* The distribution of transaction amounts is right skewed.
* This indicates that most values are clustered around the left tail of the distribution, with the longer right tail.
* 8213(0.13%) transactions are only fraud transactions.
* Remaining 6354407(99.87%) transactions are not fraud transactions.
* Higher the steps value higher the chance of fraud transaction.
* Fraudulent transactions mostly occur in cash out and transfer types.

## Evaluation
## Logistic Regression
Accuracy: 0.999217
Precision: 0.916000
Recall: 0.424074
F1 score: 0.579747
ROC AUC: 0.712012
## Logistic Regression with SMOTE
Accuracy: 0.953295
Precision: 0.952547
Recall: 0.954126
F1 score: 0.953336
ROC AUC: 0.953295
## Random Forest Classifier
Accuracy: 0.999508
Precision: 0.999086
Recall: 0.999930
F1 score: 0.999508
ROC AUC: 0.999508

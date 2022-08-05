# Spam-Text-Classification
- Spam Text Classification using Machine Learning Models
# Multi-Label Text Classification
- `stackoverflow.csv` dataset is used, which can be found via link: https://raw.githubusercontent.com/laxmimerit/All-CSV-ML-Data-Files-Download/master/stackoverflow.csv
- Tf-idf and MultiLabelBinarizer are used together to prepare train and test dataset from csv file.
- Since Logistic Regression and SVM don't support multi-class classification, OneVsRestClassifier is used.
- The One-vs-Rest strategy splits a multi-class classification into one binary classification problem per class.

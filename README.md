# Credit Card Fraud Detection
## Dataset Information
It is crucial for credit card companies to be able to identify fraudulent credit card transactions to ensure that customers are not wrongfully charged for purchases they did not make.

The dataset in question contains records of credit card transactions that occurred in September 2013, involving European cardholders. This dataset covers transactions over two days, with 492 instances of fraud detected among a total of 284,807 transactions. Notably, the dataset is heavily imbalanced, with the occurrence of frauds accounting for only 0.172% of all transactions.

The dataset primarily consists of numerical input variables resulting from a Principal Component Analysis (PCA) transformation. Unfortunately, due to confidentiality constraints, the original features and additional context about the data cannot be provided. The features labeled V1, V2, … V28 represent the principal components derived from PCA, while the 'Time' and 'Amount' features remain untransformed. 'Time' denotes the time elapsed in seconds between each transaction and the first transaction in the dataset, while 'Amount' represents the transaction amount. The 'Class' feature serves as the response variable, taking a value of 1 in cases of fraud and 0 otherwise.

Given the substantial class imbalance, it is advisable to evaluate model performance using the Area Under the Precision-Recall Curve (AUPRC) rather than relying solely on traditional confusion matrix accuracy, which may not be meaningful in unbalanced classification scenarios.
Download link: https://www.kaggle.com/mlg-ulb/creditcardfraud

**Libraries**

- pandas
- matplotlib
- seaborn
- scikit-learn

**Algorithms**

- Logistic Regression
- Random Forest
- XGBoost
Best Model F1 Score: 83.00

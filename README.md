# Credit-Card-Fraud-Detection-using-Machine-Learning-Algorithms
#### While loading the ipynb file, if 'Sorry, something went wrong. Reload?' error message appear, please visit [nbviewer](https://nbviewer.jupyter.org/) and paste the ipynb file URL to view the notebook without any inconvenience 

With increase in the number of financial transactions, the instances of fraudulent transaction have also increased. Using machine learning algorithms we will train the dataset to identify fraudulent transactions. The dataset is obtained from Kaggle.com containing information about credit card transactions made by European cardholders in September 2013 that occured in 2 days. It contains 31 features and 284,807 transactions, out of which 492 are fraudulent. The minority class denoted by 1 in the dataset accounts for only 0.17% of the total transactions, making it highly skewed. Such problems of class imbalance are also seen in face anomaly detection.

We have used PCA and t-SNE (only on undersampled data sinced t-SNE takes huge time with large data) for visualization purpose in 2D. SVM, Random Forest, and XGBoost are used for training. AUPRC, AUROC, and, Accuracy are used as metrics for model evaluation. In case of original data with class imbalance, accuracy is an useless metric for evaluation, rather, AUPRC is more appropriate. ROC curve is also plotted for each model. The feature correlation is explained by plotting Confusion Matrix, though it proved useless for the original dataset with high class imbalance.

A final report is linked with the repository which will summarize the project.

Dataset can be found [here](https://www.kaggle.com/mlg-ulb/creditcardfraud)

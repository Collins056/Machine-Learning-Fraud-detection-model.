# Machine-Learning-Fraud-detection-model.
This project involves creating a machine learning fraud detection model and then training and evaluating it using a financial fraud dataset. This model identifies suspicious or potentially fraudulent activity within the dataset with an accuracy score of more than 90%.


Challenges faced 
During this project the challenges faced includes an imbalanced distribution of fraud types (fraud and non-fraud cases) in our dataset. However by maximizing the functionalities of logistic regression (by setting class weight = balanced) helped our model to pay more attention to the minority class (fraud) during model training.


Link to the dataset: https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download


This dataset contains about 6.3 million records of transaction data for fraud detection.


Key terms used in this dataset.
CASH-IN: is the process of increasing the balance of
account by paying in cash to a merchant.
CASH-OUT: is the opposite process of CASH-IN, it
means to withdraw cash from a merchant which decreases
the balance of the account.
DEBIT: is similar process than CASH-OUT and involves sending the money from the mobile money service
to a bank account.
PAYMENT: is the process of paying for goods or services to merchants which decreases the balance of the account and increases the balance of the receiver.
TRANSFER: is the process of sending money to another user of the service through the mobile money platform.


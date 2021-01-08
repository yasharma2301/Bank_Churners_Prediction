# Bank Churners Prediction

# Problem Statement
A bank manager is uncomfortable with more and more customers leaving their credit card services. They would really appreciate it if someone could predict who will be affected so that they can proactively go to the customer to provide them with better services and turn customer decisions in the opposite direction.

Link to dataset: https://www.kaggle.com/sakshigoyal7/credit-card-customers

# Brief Overview

  - It was seen that the data was unbalanced; 16% of the data was classified as Attrited customers while 84% were not. In order to solve this, SMOTE (Synthetic Minority Oversampling Technique).
  - To reduce the curse of dimentionality PCA(Principal Component Analysis) has been used.
  - Furthermore, SVM and AdaBoost machine learning algorithms have been incorporated. Out of which AdaBoost performs slightly better, with a F1-score of 0.9386.

# Results
Confusion matrix of test data set:

![Alt text](/snap1.PNG?raw=true "Confusion Matrix")

And the precision recall curve:

![Alt text](/snap2.PNG?raw=true "Precision Recall Curve")

Access the jupyter note-book here, https://github.com/yasharma2301/Bank_Churners_Prediction/blob/master/churn.ipynb

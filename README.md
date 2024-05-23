# Abstract:
The primary aim of this study is to utilize supervised machine learning algorithms to predict the likelihood of bank customers opting to a term subscription plan i.e.  a term deposit plan in a bank telemarketing campaign. The goal is to create a prediction model that correctly categorises client preferences, enabling efficient resource management and focused marketing tactics. To build a predictive model, three distinct machine learning algorithms were employed: logistic regression, support vector machines, and decision tree algorithms. From the results, SVM achieved the best performance of 76% compared to other models.

# THE DATA SET AND DATA PREPROCESSING
The UCI Machine Learning Repository provided the dataset for this study. A Portuguese banking institution's direct marketing effort produced the data that was used in this investigation. There are 21 characteristics and 41,188 instances in the dataset with no missing values. Both qualitative and numerical data are included in the characteristics. The target variable is shown as a y variable that indicates whether a consumer has chosen to participate in a term deposit ('yes') or not ('no'). 

Follow the Jupyter Notebook for Data pre-processing and Exploratory Data Analysis.

# Models
 We use 3 different supervised machine learning algorithms:
1. Logistic Regression
2. Support Vector Machines
3. Decision Tree

# Results

While addressing imbalanced target variables we used   measures like AUC (Area Under the ROC Curve), TPR (True Positive Rate), FPR (False Positive Rate), and F1 score to gain a deeper knowledge of our model's performance.

![image](https://github.com/MadhukeshK12/Long-Term_Deposit_Subscriber_Classification_Using_Machine_Learning/assets/115413028/54e8ac11-c3b0-465f-a938-d95b7e721b04)

Fig: ROC of SVM on test data.

Comparing SVM Classifier to other algorithms, it performs the best based on the AUC and F1 score.

# Conclusion
In the month may the bank seen a lot of consumer rejections. It would be good for the bank to choose campaigning during the months of March, September, October, and December. The analysis indicates that the oldest age group has a larger possibility of subscribing to a term deposit (76%), while the lowest age group has a 60% chance.


# Fraud Detection Using Logistic Regression
I built a fraud detection model using Logistic Regression. I performed data cleaning, handled categorical variables using one-hot encoding, split data into train and test sets, and trained the model. Since fraud data is imbalanced, I used class_weight='balanced'. I evaluated using confusion matrix, precision, recall, and achieved improved fraud detection with reduced false negatives. I visualized the model performance using confusion matrix, ROC curve, and feature importance to understand fraud detection accuracy and key drivers
Workflow - Data → Cleaning → Feature Engineering → Train Model → Evaluate → Deploy API → Real-time Fraud Detection

# Project Objective:
The goal was to identify fraudulent financial transactions using a Logistic Regression model and help the business reduce financial losses by detecting suspicious activities in real time.

# Approach

* Collected transaction data containing features such as transaction amount, transaction time, device type, location, and customer transaction history.
* Performed data cleaning by handling missing values and encoding categorical variables.
* Conducted exploratory data analysis to understand fraud patterns.
* Since fraud cases were much fewer than genuine transactions, I handled the class imbalance using techniques like class weighting.
* Split the data into training and testing datasets and trained a Logistic Regression model.
* Evaluated the model using Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrix.

# Key Findings

* High-value transactions had a higher probability of fraud.
* Transactions from new devices or unusual locations showed increased fraud risk.
* Late-night transactions were more likely to be fraudulent.

# Visualizations Used

* Confusion Matrix to measure correct and incorrect fraud predictions.
* ROC Curve to evaluate model discrimination capability.
* Feature Importance chart to identify the factors contributing most to fraud.

# Business Impact

* Improved fraud detection rate.
* Reduced false negatives (fraud cases missed by the system).
* Enabled faster investigation of suspicious transactions.
* Helped minimize financial losses and operational risks.

# Fraud Detection with Data Mining

This repository explores fraud detection within transactional data using data mining techniques. The provided Jupyter notebook delves into the analysis and implementation of various machine learning algorithms to detect fraudulent activities within financial transactions.

# Dataset Overview:

The dataset used in this analysis is sourced from the IEEE-CIS Fraud Detection Kaggle competition. It comprises a comprehensive collection of transactional data, including features such as transaction amount, product code, card type, and more.

# Key Insights:

Data Exploration: The dataset comprises diverse transaction types, with 'W' being the most prevalent 'ProductCD'. Visa emerges as the dominant card issuer, mainly used for debit transactions.

Data Preprocessing: Handling missing values was crucial to ensuring data integrity, achieved by dropping incomplete entries. Categorical variables were encoded into numerical formats for compatibility with machine learning models.

Feature Analysis: Correlation analysis revealed intricate relationships between transaction attributes, offering insights into potential fraud indicators.

Visualization: KDE plots showcased distinct distributions between fraudulent and non-fraudulent transactions, emphasizing key features like 'TransactionAmt' and 'TransactionDT'.

Model Training and Evaluation: A decision tree classifier was trained on the data, and its performance was evaluated using the ROC-AUC curve, demonstrating its effectiveness in distinguishing between genuine and fraudulent transactions.

# Conclusion:

This repository underscores the significance of data mining in uncovering patterns within transactional data, enabling financial institutions to proactively mitigate risks and safeguard against fraudulent activities effectively.

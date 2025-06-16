Urgency Classification in MOOC Forum Posts
 Project Summary
This project is a data analytics and machine learning solution to identify urgent posts in a MOOC (Massive Open Online Course) forum using a dataset from Stanford. The primary goal is to detect posts that require immediate attention, helping teaching assistants and moderators prioritize their responses more effectively.

 Dataset
Source: Stanford MOOC forum dataset

Structure: Text posts with metadata and urgency labels

Target Variable: urgent (binary classification)

 Project Steps
Data Preprocessing

Null handling

Categorical encoding (Label Encoding & One-Hot Encoding)

Scaling numerical features

Outlier detection using Isolation Forest

Exploratory Data Analysis (EDA)

Visualization of feature distributions

Correlation matrix and feature importance

Feature Engineering

Text-based features (length, punctuation, keyword presence)

Interaction features

Model Building

Logistic Regression as baseline

Model evaluation with Weighted F1 Score and Urgent F1 Score

Threshold tuning for performance optimization

 Results
Achieved a high Weighted F1 Score and Urgent F1 Score, with model performance monitored and improved using GridSearchCV and threshold optimization.

Bonus challenge completed: exceeded required threshold for urgent class detection.

 Tools & Libraries
Python, NumPy, pandas, matplotlib, seaborn

scikit-learn (for preprocessing and modeling)

imblearn (for handling imbalanced data)

IsolationForest (for anomaly detection)

 File Structure
DataAnalyticsProject.ipynb: Complete notebook with preprocessing, modeling, and evaluation steps.

README.md: Project overview and technical summary.




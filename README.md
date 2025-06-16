# Urgency Classification in MOOC Forum Posts

 📄 Project Overview

This project presents a data analytics and machine learning pipeline for classifying urgency in forum posts from Stanford's MOOC discussion datasets. The goal is to automatically detect posts marked as "urgent" to help moderators and teaching assistants prioritize their responses.

---

📁 Dataset Details

* **Source:** Stanford MOOC forum dataset
* **Content:** Forum posts with associated features and urgency labels
* **Target:** Binary label indicating if the post is urgent (`urgent=1`) or not (`urgent=0`)

---

🔎 Project Workflow

 1. Data Preprocessing

* Handled missing values
* Encoded categorical features using Label Encoding and One-Hot Encoding
* Scaled numeric features
* Detected and removed outliers using **Isolation Forest**

 2. Exploratory Data Analysis (EDA)

* Analyzed distribution of features
* Visualized urgency class distribution
* Generated correlation matrix and assessed feature importance

 3. Feature Engineering

* Created features from post text: length, punctuation count, presence of keywords
* Added interaction features between text and metadata

 4. Modeling

* Used **Logistic Regression** as baseline
* Applied **GridSearchCV** and **threshold tuning** to improve results
* Evaluated model using:

  * **Weighted F1 Score**
  * **Urgent-class F1 Score**

---

 🚀 Results

* Achieved high performance exceeding bonus thresholds:

  * **Weighted F1 >= 95%**
  * **Urgent-class F1 >= 90%**
* Demonstrated effectiveness of preprocessing and feature engineering in improving classification accuracy

---

 🛠️ Tech Stack

* Python
* Jupyter Notebook
* pandas, numpy, matplotlib, seaborn
* scikit-learn, imbalanced-learn
* IsolationForest for outlier detection

---

📂 Repository Contents

* `DataAnalyticsProject.ipynb`: Full notebook including preprocessing, modeling, and evaluation
* `README.md`: Project summary and instructions

---

 🌟 Acknowledgments

* Based on a machine learning project using a dataset provided by Stanford University MOOCs

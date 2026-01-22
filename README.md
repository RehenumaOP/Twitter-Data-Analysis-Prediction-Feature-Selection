📊 Twitter Dataset – Machine Learning Lab Project

This repository contains my Machine Learning Lab Assignment based on a Twitter dataset.
The project covers data preprocessing, feature engineering, feature selection methods, and machine learning algorithms, implemented step-by-step using Python.

📁 Dataset Description

Dataset name: Twitter data

Number of records: 100,000+

Number of features: 14

Data type: Mixed (Numerical, Categorical, Text)


🎯 Project Objectives

1.Understand and describe the dataset

2.Handle missing values properly

3.Perform feature engineering

4.Apply feature selection techniques

5.Implement machine learning algorithms

6.Split data and validate models

7.Analyze results and findings

🛠️ Tasks Performed
1️⃣ Dataset Description

Dataset structure and feature types analyzed using info() and describe()

2️⃣ Handling Missing Data

1.Numerical features filled using median

2.Categorical features filled using mode

3.Column names cleaned to remove extra spaces

3️⃣ Feature Engineering

Categorical encoding (Label Encoding)

New feature created:
Engagement = Likes + RetweetCount

Removed irrelevant ID columns

4️⃣ Gradient Descent Algorithm

1.Linear Regression applied to predict Likes

2.Features scaled using StandardScaler

3.Cost evaluated using Mean Squared Error (MSE)

5️⃣ Distance-Based Algorithm

1.K-Nearest Neighbors (KNN) used

2.Euclidean distance applied

3.Binary popularity classification performed

🔍 Feature Selection Methods
6️⃣ Filter Method

1.Correlation-based feature selection

2.Variance Threshold method

7️⃣ Wrapper Method

Forward feature selection using Linear Regression

Model performance (R² score) used for selection

8️⃣ Embedded Method

LASSO Regression

Decision Tree feature importance

9️⃣ Data Size Filter Method

Removed duplicate rows

Removed low-engagement tweets to reduce noise

✂️ Dataset Splitting

Training Set: 60%

Validation Set: 20%

Test Set: 20%

Used to avoid overfitting and tune model parameters.

📈 Findings & Observations

Tweets with higher Klout score receive more likes

Reach and RetweetCount are highly influential features

Engagement increases with reposts

Feature selection improves model performance

🧪 Tools & Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

📂 Repository Structure
├── Twitter.ipynb
├── Twitter_data.xlsx
└── README.md

✅ How to Run the Project

Clone the repository

git clone https://github.com/your-username/twitter-ml-lab.git


Open the notebook

jupyter notebook Twitter.ipynb


Run cells step by step

👨‍🎓 Author

Name: Rehenuma Tarin Tuhi

Course: Machine Learning Lab



📌 Notes

This project is created for academic and learning purposes only.

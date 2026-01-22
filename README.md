📊 Twitter Dataset – 

This repository contains my Machine Learning Lab Assignment based on a Twitter dataset.
The project covers data preprocessing, feature engineering, feature selection methods, and machine learning algorithms, implemented step-by-step using Python.

📁 Dataset Description

Dataset name: Twitter data

Number of records: 100,000+

Number of features: 14

Data type: Mixed (Numerical, Categorical, Text)

Dataset Columns
Column Name	Description
TweetID	Unique tweet identifier
Weekday	Day of posting
Hour	Hour of posting
Day	Day of month
Lang	Tweet language
IsReshare	Retweet indicator
Reach	Number of users reached
RetweetCount	Number of retweets
Likes	Number of likes
Klout	User influence score
Sentiment	Sentiment score
text	Tweet text
LocationID	Location identifier
UserID	User identifier
🎯 Project Objectives

Understand and describe the dataset

Handle missing values properly

Perform feature engineering

Apply feature selection techniques

Implement machine learning algorithms

Split data and validate models

Analyze results and findings

🛠️ Tasks Performed
1️⃣ Dataset Description

Dataset structure and feature types analyzed using info() and describe()

2️⃣ Handling Missing Data

Numerical features filled using median

Categorical features filled using mode

Column names cleaned to remove extra spaces

3️⃣ Feature Engineering

Categorical encoding (Label Encoding)

New feature created:
Engagement = Likes + RetweetCount

Removed irrelevant ID columns

4️⃣ Gradient Descent Algorithm

Linear Regression applied to predict Likes

Features scaled using StandardScaler

Cost evaluated using Mean Squared Error (MSE)

5️⃣ Distance-Based Algorithm

K-Nearest Neighbors (KNN) used

Euclidean distance applied

Binary popularity classification performed

🔍 Feature Selection Methods
6️⃣ Filter Method

Correlation-based feature selection

Variance Threshold method

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

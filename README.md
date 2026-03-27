# Mercedes--Benz-Greener-Manufacturing
Mercedes-Benz Greener Manufacturing 🚗🌱
📌 Project Overview

This project aims to reduce the time a Mercedes-Benz car spends on the test bench by predicting testing time using machine learning techniques.
By optimizing predictions, the manufacturing process becomes faster and more efficient, reducing carbon emissions.

🎯 Problem Statement

Mercedes-Benz produces cars with many feature combinations. Each configuration requires testing before release.
The goal is to build a model that predicts test bench time based on car features.

🛠️ Tasks Performed
✔️ Removed zero-variance columns
✔️ Checked for null values
✔️ Label Encoding for categorical variables
✔️ Dimensionality Reduction using PCA
✔️ Model training using XGBoost
✔️ Generated predictions for test dataset
📂 Dataset
train.csv → Training dataset with target variable y
test.csv → Test dataset for predictions
⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
XGBoost
Jupyter Notebook
🚀 Workflow
Load Dataset
Remove Zero Variance Columns
Handle Missing Values
Label Encode Categorical Features
Apply PCA for Dimensionality Reduction
Train XGBoost Regressor
Evaluate Model (R² Score)
Predict Test Data
Create Submission File
📊 Model Used

XGBoost Regressor

n_estimators = 500
learning_rate = 0.05
max_depth = 4
subsample = 0.8
colsample_bytree = 0.8
▶️ How to Run
git clone <your-repo-link>
cd Mercedes-Benz-Greener-Manufacturing

Open Jupyter Notebook and run:

Mercedes_Benz_Greener_Manufacturing.ipynb
📈 Output

The model generates:

submission.csv

with predicted test bench time.

📁 Project Structure
Mercedes-Benz-Greener-Manufacturing
│
├── train.csv
├── test.csv
├── Mercedes_Benz_Greener_Manufacturing.ipynb
├── submission.csv
└── README.md
✨ Future Improvements
Hyperparameter tuning
Feature selection
Ensemble models
Cross-validation
👩‍💻 Author

Mugdha Khobare
Machine Learning Enthusiast

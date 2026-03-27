# 🚗 Mercedes-Benz Greener Manufacturing

> Machine Learning project to predict and reduce the time a Mercedes-Benz car spends on the test bench.

---

## 📖 Project Description

Mercedes-Benz manufactures premium cars with multiple feature combinations. Each unique configuration requires testing before delivery.
This project builds a **machine learning model** that predicts test bench time using feature data, helping optimize manufacturing efficiency and reduce carbon emissions. 🌱

---

## 🎯 Objectives

* Reduce testing time
* Improve production efficiency
* Apply dimensionality reduction techniques
* Build an optimized regression model
* Generate predictions for unseen data

---

## 📂 Dataset Information

The project uses two datasets:

| File        | Description                            |
| ----------- | -------------------------------------- |
| `train.csv` | Training data with target variable `y` |
| `test.csv`  | Test data for prediction               |

Target variable:

* **y** → Time spent on test bench

---

## 🛠️ Technologies & Libraries

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## ⚙️ Project Workflow

1. Load datasets
2. Remove zero-variance features
3. Check missing values
4. Encode categorical variables (Label Encoding)
5. Apply PCA (Dimensionality Reduction)
6. Split training and validation data
7. Train XGBoost Regressor
8. Evaluate model using R² Score
9. Predict test dataset
10. Generate submission file

---

## 🧠 Model Used

### XGBoost Regressor

```python
XGBRegressor(
    n_estimators=500,
    learning_rate=0.05,
    max_depth=4,
    subsample=0.8,
    colsample_bytree=0.8,
    random_state=42
)
```

---

## 📊 Evaluation Metric

* **R² Score** (Coefficient of Determination)

Higher score indicates better model performance.

---

## 📁 Project Structure

```
Mercedes-Benz-Greener-Manufacturing
│
├── train.csv
├── test.csv
├── Mercedes_Benz_Greener_Manufacturing.ipynb
├── submission.csv
└── README.md
```

---

## ▶️ How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/Mercedes-Benz-Greener-Manufacturing.git
```

### Step 2: Navigate to Folder

```bash
cd Mercedes-Benz-Greener-Manufacturing
```

### Step 3: Install Dependencies

```bash
pip install pandas numpy scikit-learn xgboost
```

### Step 4: Run Notebook

Open Jupyter Notebook and run:

```
Mercedes_Benz_Greener_Manufacturing.ipynb
```

---

## 📈 Output

The model generates:

```
submission.csv
```

Containing:

* ID
* Predicted test bench time

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Ensemble learning
* Cross-validation
* Deep learning approach

---

## 👩‍💻 Author

**Mugdha Khobare**

Machine Learning Enthusiast 🚀



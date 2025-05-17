
# 🏥 Life Insurance Premium Prediction using Machine Learning

This project aims to **predict insurance premiums** for life insurance applicants using machine learning models, developed as a mini-project at **Central Institute of Technology Kokrajhar**.

---

## 📌 Project Overview

This web-based application predicts life insurance premiums based on user inputs such as age, sex, BMI, number of children, smoker status, and region. A trained ML model (Gradient Boosting Regressor) provides predictions.

---

## 📂 Project Structure

```
├── app.py                         # Flask app to serve the prediction model
├── Insurance Premium Prediction.ipynb  # Jupyter Notebook for model training and evaluation
├── insurance.csv                  # Dataset used for training
├── model.pkl                      # Serialized ML model using pickle
├── templates/
│   ├── index.html                 # Frontend form for input
│   └── result.html                # Displays predicted premium
├── static/
│   └── style.css                  # CSS styling
```

---

## 🧠 Machine Learning Approach

- **Dataset:** [Kaggle Health Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Features:** `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`
- **Algorithms Tried:**
  - Linear Regression
  - Random Forest Regressor
  - Support Vector Regressor
  - **Gradient Boosting Regressor** (Best Performer)

---

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/insurance-premium-prediction.git
cd insurance-premium-prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Flask app

```bash
python app.py
```

### 4. Open your browser

Visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🎯 Results

- **Best Accuracy:** ~86%
- **Best Model:** Gradient Boosting Regressor
- **Evaluation Metrics:** R² Score, Mean Absolute Error

---

## 📈 Screenshot

![Screenshot](Screenshot%202025-05-17%20at%208.35.12%E2%80%AFAM.png)

---

## 👨‍💻 Developed By

Students of **CIT Kokrajhar**, Department of Computer Science & Engineering.

---

## 📚 References

- "Insurance Risk Prediction Using Machine Learning", 2023
- "Life Insurance Prediction Using ML", 2023
- Kaggle Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance

---

> This project demonstrates how machine learning can be used to modernize and improve the insurance industry through predictive analytics.


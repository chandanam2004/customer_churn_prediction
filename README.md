# 📊 Customer Churn Prediction Dashboard

A Machine Learning-powered web application that predicts whether a customer is likely to churn based on behavioral, transactional, and engagement-related data.

Built using **Python**, **Scikit-learn**, and **Streamlit**.

---

# 🚀 Project Overview

Customer churn prediction is an important business problem that helps companies identify customers who may stop using their services or products.

This project uses a trained Machine Learning model to analyze customer patterns and predict:

* ✅ Customer Will Stay
* ❌ Customer Likely to Churn

The application provides an interactive dashboard where users can enter customer details and receive instant predictions.

---

# 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Streamlit
* Pickle

---

# 📌 Features

### ✅ Interactive Streamlit Dashboard

User-friendly interface for entering customer information.

### ✅ Real-Time Predictions

Instant churn prediction using a trained ML model.

### ✅ Data Preprocessing

* Binary Encoding
* One-Hot Encoding
* Feature Alignment

### ✅ Test Scenarios

Includes:

* High-Risk Customer
* Low-Risk Customer

### ✅ Machine Learning Integration

Loads trained model and prediction columns using Pickle.

---

# 📂 Project Structure

```bash
Customer-Churn-Prediction/
│
├── app.py                 # Streamlit application
├── model.pkl              # Trained ML model
├── columns.pkl            # Saved feature columns
├── requirements.txt       # Required dependencies
└── README.md              # Project documentation
```

---

# ⚙️ How It Works

## 1️⃣ User Input

The user enters customer information such as:

* Age
* Income
* Spending Score
* Purchase Amount
* Returns
* Review Score
* Session Time
* Activity Status
* Product Category
* Payment Method
* Device Type

---

## 2️⃣ Data Preprocessing

The application:

* Converts categorical values into numerical format
* Applies binary encoding
* Applies one-hot encoding
* Aligns data with training columns

---

## 3️⃣ Model Prediction

The trained Machine Learning model analyzes customer behavior patterns and predicts whether the customer is likely to churn.

```python
prediction = model.predict(input_df)[0]
```

---

# 📊 Sample Output

### ❌ Customer is likely to CHURN

or

### ✅ Customer will STAY

---

# 🧠 Machine Learning Concepts Used

* Classification
* Feature Engineering
* One-Hot Encoding
* Binary Encoding
* Model Serialization
* Real-Time Inference

---

# 🚀 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Streamlit App

```bash
streamlit run app.py
```

---

# 📈 Future Improvements

* Add churn probability visualization
* Feature importance charts
* Explainable AI (SHAP/LIME)
* Database integration
* Cloud deployment
* User authentication

---

# 🎯 Learning Outcomes

This project helped improve understanding of:

* Machine Learning workflows
* Data preprocessing
* Customer analytics
* Model deployment
* Interactive dashboard development

---

# 📬 Contact

If you'd like to connect or discuss improvements, feel free to reach out!

LinkedIn: your-linkedin-profile
GitHub: your-github-profile

---

# ⭐ If you found this project useful, consider giving it a star!

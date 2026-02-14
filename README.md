# 💳 Fraud Detection Web App

A simple **Machine Learning web application** built with **Streamlit** that predicts whether a financial transaction is **fraudulent or legitimate** based on transaction details.

---
## 📌 Features

* Interactive web interface
* Real-time fraud prediction
* User-friendly input form
* Machine Learning pipeline integration
* Instant result display

---

## 🧠 Machine Learning Model

The model was trained using transaction features such as:

* Transaction type
* Amount
* Sender balance before transaction
* Sender balance after transaction
* Receiver balance before transaction
* Receiver balance after transaction

The trained pipeline is saved as:

```
fraud_detection_pipeline.pkl
```

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* Scikit-learn
* Joblib

---

## 📂 Project Structure

```
fraud-detection/
│
├── fraud_detection.py              # Streamlit app
├── fraud_detection_pipeline.pkl    # Trained ML model
├── requirements.txt                # Dependencies
├── runtime.txt                     # Python version
└── README.md
```

---

## ⚙️ Installation (Run Locally)

1️⃣ Clone the repository

```
git clone https://github.com/YOUR-USERNAME/fraud-detection.git
cd fraud-detection
```

2️⃣ Install dependencies

```
pip install -r requirements.txt
```

3️⃣ Run the app

```
streamlit run fraud_detection.py
```

---

## 🌐 Deployment

This app is deployed using **Streamlit Cloud**.

Steps:

1. Push code to GitHub
2. Connect repository on Streamlit Cloud
3. Deploy the app

---

## 📊 How It Works

1. User enters transaction details
2. Data is converted into a dataframe
3. Model pipeline processes inputs
4. Prediction is displayed instantly

---

## 🎯 Use Cases

* Fraud risk screening
* Educational ML project
* Finance analytics demo
* Portfolio project

---

## 📜 License

This project is for **educational purposes only**.

---

⭐ If you like this project, consider giving it a star!

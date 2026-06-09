# 🏥 InsuraMind – Insurance Premium Category Prediction

## 📌 Overview

**InsuraMind** is a Machine Learning-powered web application that predicts the **insurance premium category** of a customer based on personal and demographic information. The project combines a trained Machine Learning model with a FastAPI backend and a Streamlit frontend to provide real-time predictions through an interactive user interface.

The primary goal of this project is to assist insurance providers and customers by estimating the premium category efficiently and accurately.

---

## 🎯 Problem Statement

Insurance companies determine premium amounts based on multiple factors such as age, income, health status, lifestyle habits, and other customer attributes. Manually evaluating these factors can be time-consuming and inconsistent.

InsuraMind automates this process by using Machine Learning to predict the most suitable insurance premium category.

---

## ✨ Features

* Predict insurance premium categories instantly.
* User-friendly web interface built with Streamlit.
* Fast and efficient API using FastAPI.
* Machine Learning model trained on insurance-related data.
* Real-time prediction results.
* Easy deployment and scalability.

---

## 🛠️ Tech Stack

### Machine Learning

* Python
* Scikit-Learn
* Pandas
* NumPy

### Backend

* FastAPI
* Uvicorn

### Frontend

* Streamlit

### Model Storage

* Pickle (`model.pkl`)

---

## 📂 Project Structure

```text
Insurance-premium-prediction/
│
├── app.py                      # FastAPI backend
├── frontend.py                 # Streamlit frontend
├── fastapi_ml_model.ipynb      # Model training notebook
├── model.pkl                   # Trained ML model
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
├── LICENSE
│
├── .ipynb_checkpoints/
│
└── __pycache__/
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Insurance-premium-prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Insurance-premium-prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Running the Application

### Step 1: Start the FastAPI Server

```bash
uvicorn app:app --reload
```

FastAPI will run at:

```text
http://127.0.0.1:8000
```

---

### Step 2: Start the Streamlit Frontend

Open a new terminal and run:

```bash
streamlit run frontend.py
```

Streamlit will run at:

```text
http://localhost:8501
```

---

## 🔄 Workflow

1. User enters insurance-related information through the Streamlit interface.
2. Streamlit sends the data to the FastAPI backend.
3. FastAPI loads the trained machine learning model (`model.pkl`).
4. The model predicts the insurance premium category.
5. The prediction is returned and displayed to the user.

---

## 📊 Machine Learning Pipeline

* Data Collection
* Data Cleaning
* Feature Engineering
* Model Training
* Model Evaluation
* Model Serialization using Pickle
* API Integration with FastAPI
* Frontend Integration with Streamlit

---

## 🎯 Use Cases

* Insurance companies
* Insurance agents
* Risk assessment systems
* Customer premium estimation
* Educational Machine Learning projects

---

## 🔮 Future Enhancements

* Premium amount prediction instead of category prediction.
* Deployment on cloud platforms.
* User authentication system.
* Advanced analytics dashboard.
* Explainable AI predictions.
* Database integration for prediction history.

---

## 👨‍💻 Author

### Jaychandra Das

B.Tech Student | Machine Learning Enthusiast | Python Developer

---

## 📜 License

This project is licensed under the terms specified in the LICENSE file.

---

### "InsuraMind – Smart Insurance Premium Prediction Powered by Machine Learning."

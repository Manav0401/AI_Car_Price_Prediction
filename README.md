# 🚗 AI Car Price Predictor

An AI-powered web application that predicts the resale value of used cars using Machine Learning. Built with **Flask**, **Scikit-learn**, and **Python**, this application provides an intuitive interface for estimating vehicle prices based on various car attributes.

---

## 📖 Overview

The AI Car Price Predictor is designed to estimate the market value of a used vehicle based on its specifications. The application uses a trained Machine Learning model to analyze user-provided vehicle information and generate an estimated resale price.

The project demonstrates the complete workflow of a Machine Learning application, including:

- Data preprocessing
- Model training
- Model serialization
- Flask backend
- Interactive frontend
- Real-time predictions

---

## ✨ Features

- 🚗 Brand and model selection
- 🔍 Searchable dropdown menus
- ⚡ Automatic vehicle specification loading
- 🤖 Machine Learning price prediction
- 📱 Responsive user interface
- 🎨 Modern animated frontend
- 💾 Pre-trained ML model
- 📊 Instant resale price estimation

---

## 🛠 Technologies Used

### Backend

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- Joblib

### Frontend

- HTML5
- CSS3
- JavaScript
- Tom Select

### Machine Learning

- Regression Model
- Data Preprocessing
- Feature Engineering
- Model Serialization using Joblib

---

## 📂 Project Structure

```
CAR_PRICE_PREDICTION/
│
├── app.py
├── requirements.txt
├── README.md
├── render.yaml
│
├── data/
│   └── cleaned_dataset.csv
│
├── model/
│   └── best_model.pkl
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    └── index.html
```

---

## 📊 Dataset Features

The model predicts car prices using the following features:

- Brand
- Model
- Vehicle Age
- Kilometers Driven
- Seller Type
- Fuel Type
- Transmission Type
- Mileage
- Engine Capacity
- Maximum Power
- Number of Seats

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/Manav0401/AI-Car-Price-Predictor.git
```

Move into the project directory

```bash
cd AI-Car-Price-Predictor
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

## 🚀 How It Works

1. Select the vehicle brand.
2. Choose the vehicle model.
3. Enter the manufacturing year.
4. Enter kilometers driven.
5. Select fuel type.
6. Select transmission type.
7. Select seller type.
8. Click **Predict Price**.
9. The trained Machine Learning model estimates the resale value.

---

## 🧠 Machine Learning Workflow

```
Dataset
     │
     ▼
Data Cleaning
     │
     ▼
Feature Engineering
     │
     ▼
Model Training
     │
     ▼
Model Evaluation
     │
     ▼
Model Serialization (.pkl)
     │
     ▼
Flask Application
```

---

## 📸 Screenshots

### Homepage

![Homepage](assets/homepage.png)

---

### Prediction Result

![Prediction](assets/result.png)

---

### Mobile View

![Mobile](assets/mobile.jpeg)
---

## 🌐 Deployment

The application can be deployed using:

- Render
- Railway
- PythonAnywhere

---

## 🔮 Future Improvements

- User authentication
- Prediction history
- Price trend visualization
- Vehicle image recognition
- AI-powered recommendations
- Dark mode
- Comparison with market prices
- REST API support

---

## 👨‍💻 Author

**Manav M George**

Integrated M.Tech in Artificial Intelligence

VIT Bhopal University

---
This project is intended for educational and portfolio purposes.

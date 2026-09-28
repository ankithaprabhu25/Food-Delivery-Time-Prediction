# 🍔 Food Delivery Time Prediction

A Machine Learning web application that predicts **food delivery time** based on delivery-related features. The project includes data preprocessing, exploratory data analysis, regression models, model evaluation, and a Flask-based web application with a user-friendly frontend.

## 🚀 Features

* Predicts food delivery time using Machine Learning
* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Categorical data encoding
* Feature scaling
* Multiple regression models
* Model evaluation and comparison
* Flask web application
* User-friendly frontend
* Saved trained model and preprocessing files

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Flask
* HTML
* CSS
* Jupyter Notebook
* Pickle

## 🤖 Machine Learning Models

The project explores multiple regression algorithms:

* Linear Regression
* Decision Tree Regression
* Random Forest Regression
* Support Vector Regression (SVR)

The Flask web application uses the trained prediction model to estimate food delivery time.

## 📂 Project Structure

```text
FOOD_PROJECT/
│
├── app.py
├── Food_Delivery_Time_Prediction.ipynb
│
├── delivery_time_model.pkl
├── model_columns.pkl
├── traffic_encoder.pkl
├── delivery_scaler.pkl
│
├── static/
│   └── ...
│
├── templates/
│   └── ...
│
├── .gitignore
└── README.md
```

## 📊 Project Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Regression Models
   ↓
Model Evaluation
   ↓
Save Trained Model
   ↓
Flask Web Application
   ↓
Food Delivery Time Prediction
```

## 🖥️ Screenshots

### 📸 Screenshot 1

<!-- Add your first screenshot here -->

<br><br><br>

### 📸 Screenshot 2

<!-- Add your second screenshot here -->

<br><br><br>

### 📸 Screenshot 3

<!-- Add your third screenshot here -->

<br><br><br>

### 📸 Screenshot 4

<!-- Add your fourth screenshot here -->

<br><br><br>

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/ankithaprabhu25/Food-Delivery-Time-Prediction.git
```

### 2. Open the project folder

```bash
cd Food-Delivery-Time-Prediction
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Flask application

```bash
python app.py
```

Open the local URL shown in the terminal, usually:

```text
http://127.0.0.1:5000/
```

## 🎯 Purpose

The goal of this project is to use Machine Learning to estimate food delivery time and provide the prediction through a simple web-based interface.

## 👩‍💻 Author

**Ankitha Prabhu**

GitHub:
https://github.com/ankithaprabhu25

## 📌 Future Improvements

* Improve prediction accuracy
* Add more advanced Machine Learning models
* Improve the user interface
* Deploy the application online
* Add real-time prediction features


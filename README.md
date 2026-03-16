# Fraud Detection In Internet Banking using ML

This project develops a **machine learning-based fraud detection system** for identifying fraudulent transactions in internet banking.  
The system analyzes transaction data and predicts whether a transaction is **fraudulent or legitimate**.

The project also includes a **web-based interface** where users can input transaction details and receive fraud predictions.

---

## Project Overview

Online banking systems process thousands of transactions daily, making them vulnerable to fraudulent activities.  
This project uses **machine learning techniques** to detect suspicious transactions and reduce financial fraud.

The trained model analyzes transaction features and predicts the likelihood of fraud.

---

## Dataset

The project uses a dataset containing banking transaction details.

Typical features include:

- Transaction amount
- Transaction type
- Account balances
- Origin account
- Destination account
- Transaction time

The dataset is stored in: model/fraud.csv

---

## Technologies Used

Programming Language  
Python

Machine Learning  
Scikit-learn  
Pandas  
NumPy

Web Framework  
Flask

Frontend  
HTML  
CSS  
JavaScript  
Bootstrap

Visualization  
Matplotlib  
Seaborn

---

## Machine Learning Workflow

1. Load transaction dataset
2. Perform data preprocessing
3. Handle missing values
4. Feature selection and transformation
5. Train machine learning model
6. Evaluate model performance
7. Save trained model using Pickle
8. Integrate model into web application

---

## Model Training

The model is trained using historical transaction data to learn patterns associated with fraudulent activities.

Steps involved:

- Data cleaning
- Feature engineering
- Model training
- Model evaluation
- Model serialization

The trained model is saved as: model.pkl

---

## Web Application

The project includes a **Flask-based web interface** where users can:

1. Enter transaction information
2. Submit transaction details
3. Receive fraud prediction results

Key files:

run.py

templates/

static/

The system processes the input data and uses the trained model to predict whether the transaction is **fraudulent or safe**.

---

## Project Structure

Fraud-Detection-In-Internet-Banking-using-ML

model/
fraud.csv
model.pkl
TraningModel.ipynb

templates/
index.html
input.html
login.html
about.html
contact.html

static/
css/
js/
images/

run.py

---

## How to Run the Project

Clone the repository: git clone https://github.com/BhavanaTallapaka/Fraud-Detection-In-Internet-Banking-using-ML.git

Install dependencies

pip install flask pandas numpy scikit-learn matplotlib seaborn

Run the application

python run.py

Open the browser

http://127.0.0.1:5000

Enter transaction details and check fraud prediction.

---

## Application Screenshots

### Home Page

![Home Page](screenshots/home.png)

### Transaction Input Form

![Input Form](screenshots/input.png)

### Fraud Prediction Result

![Prediction Result](screenshots/result.png)

---

## Features

• Machine learning-based fraud detection  
• Real-time fraud prediction  
• User-friendly web interface  
• Model saved for reuse  
• Transaction data analysis  

---

## Future Improvements

Possible improvements include:

- Using advanced algorithms such as **XGBoost or LightGBM**
- Adding **deep learning models**
- Real-time banking API integration
- Deploying the system on **cloud platforms**
- Improving fraud detection accuracy with larger datasets

---

## Author

Bhavana Tallapaka  
Computer Science Engineering Student

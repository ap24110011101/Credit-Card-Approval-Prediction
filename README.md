# 💳 Credit Card Approval Prediction System

## 📌 Project Overview

The Credit Card Approval Prediction System is a Machine Learning-based web application designed to predict whether a credit card application is likely to be approved or rejected.

The system analyzes applicant financial and demographic information and uses a trained Machine Learning model to provide an instant prediction.

The trained model is integrated with a Flask web application and deployed on Render for online access.

---

## 🎯 Objective

The main objective of this project is to automate the credit card approval screening process using Machine Learning.

The system helps reduce manual processing time and supports faster credit card eligibility prediction.

---

## 🚀 Features

- Credit card approval prediction
- Machine Learning-based classification
- User-friendly web interface
- Real-time prediction
- Applicant financial data analysis
- Automated approval and rejection result
- Flask web application
- Cloud deployment using Render

---

## 🤖 Machine Learning Algorithms

The following Machine Learning algorithms were considered:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. XGBoost Classifier

The best-performing model is selected and saved for prediction.

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-learn
- XGBoost
- NumPy
- Pandas

### Web Development

- Flask
- HTML
- CSS

### Development Tools

- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

### Deployment

- Render
- Gunicorn

---

## 📂 Project Structure

    credit-card-approval-predictions/
    │
    ├── app.py
    ├── requirements.txt
    │
    ├── models/
    │   └── model.pkl
    │
    ├── templates/
    │   ├── home.html
    │   ├── index.html
    │   └── result.html
    │
    ├── static/
    │   └── style.css
    │
    ├── dataset/
    │   ├── application_record.csv
    │   └── credit_record.csv
    │
    ├── notebooks/
    │   └── credit_card_prediction.ipynb
    │
    └── README.md

---

## ⚙️ Project Workflow

1. Collect the credit card applicant dataset.
2. Load the dataset using Pandas.
3. Perform data preprocessing and cleaning.
4. Handle missing and duplicate values.
5. Convert categorical data into numerical values.
6. Perform feature engineering.
7. Split the dataset into training and testing data.
8. Train multiple Machine Learning models.
9. Evaluate and compare model performance.
10. Select the best-performing model.
11. Save the trained model using Joblib.
12. Integrate the model with Flask.
13. Create a web-based user interface.
14. Deploy the application on Render.

---

## 🔄 Application Flow

    User Enters Applicant Details
                  ↓
          Flask Web Application
                  ↓
          Data Input Processing
                  ↓
        Trained Machine Learning Model
                  ↓
             Prediction
                  ↓
        Approved / Rejected

---

## 💻 How to Run the Project Locally

### Step 1: Clone the Repository

    git clone <your-repository-url>

### Step 2: Navigate to the Project Folder

    cd credit-card-approval-predictions

### Step 3: Install Required Libraries

    pip install -r requirements.txt

### Step 4: Run the Flask Application

    python app.py

### Step 5: Open the Application

Open the local Flask server address displayed in the terminal.

Usually:

    http://127.0.0.1:5000

---

## 📊 Input Features

The prediction system uses applicant details such as:

- Gender
- Car ownership
- Property ownership
- Number of children
- Total income
- Income type
- Education type
- Family status
- Housing type
- Age information
- Employment duration
- Mobile availability
- Work phone availability
- Phone availability
- Email availability
- Number of family members

---

## 📈 Prediction Result

The system predicts one of the following outcomes:

- ✅ Credit Card Approved
- ❌ Credit Card Rejected

---

## ☁️ Deployment

The Flask Machine Learning application is deployed using Render.

Gunicorn is used as the production WSGI server to run the Flask application.

---

## 🔮 Future Improvements

- Add credit risk score prediction
- Add approval probability percentage
- Improve model accuracy
- Add applicant history dashboard
- Add explainable AI features
- Implement secure user authentication
- Integrate a database
- Add batch applicant prediction

---

## 📌 Conclusion

The Credit Card Approval Prediction System demonstrates how Machine Learning can automate financial application screening.

The system processes applicant information and provides quick approval or rejection predictions through a simple Flask web application.

This project reduces manual effort, improves processing speed, and demonstrates the practical integration of Machine Learning with web technologies.

---

## 👨‍💻 Project Type

Machine Learning and Flask Web Application

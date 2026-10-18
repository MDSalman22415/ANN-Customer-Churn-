# ANN Customer Churn Prediction

An Artificial Neural Network (ANN) based machine learning web application that predicts whether a bank customer is likely to leave the bank based on customer-related information.

The application provides an interactive interface built with Streamlit, allowing users to enter customer details and obtain a churn prediction from a trained neural network model.

## 🚀 Live Demo

**Try the application here:**  
https://annclassficationchurn.streamlit.app/

## 📌 Project Overview

Customer churn refers to the situation in which a customer stops using a company's products or services. Predicting churn helps businesses identify customers who may leave and take proactive steps to improve customer retention.

This project uses an Artificial Neural Network (ANN) to classify customers into churn and non-churn categories based on relevant customer attributes.

## 🎯 Objectives

- Predict customer churn using an ANN model.
- Apply data preprocessing and feature encoding techniques.
- Understand the implementation of deep learning for a binary classification problem.
- Deploy a machine learning model through an interactive web application.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **TensorFlow / Keras** — Building and loading the ANN model
- **Pandas** — Data manipulation and preprocessing
- **NumPy** — Numerical computations
- **Scikit-learn** — Data preprocessing and encoding
- **Streamlit** — Interactive web application and deployment

## 🧠 Machine Learning Workflow

1. **Data Collection:** Load the customer churn dataset.
2. **Data Preprocessing:** Prepare the input features for model training and prediction.
3. **Feature Encoding:** Convert categorical features, such as Geography, into numerical representations using One-Hot Encoding.
4. **Feature Scaling:** Scale numerical features using the preprocessing method used during training.
5. **ANN Model:** Use a trained Artificial Neural Network for binary classification.
6. **Prediction:** Process user-provided customer information and generate a churn prediction.
7. **Deployment:** Make the model accessible through a Streamlit web application.

## ⚙️ Key Features

- Interactive customer information input.
- Categorical feature encoding.
- Neural network-based churn prediction.
- Web-based interface accessible through a browser.
- Live deployment using Streamlit Community Cloud.

## 📂 Project Structure

```text
ANN-Customer-Churn-Prediction/
│
├── app.py                     # Streamlit application
├── requirements.txt           # Python dependencies
├── model.h5                   # Trained ANN model (if included)
├── scaler.pkl                 # Fitted feature scaler (if included)
├── label_encoder_gender.pkl   # Gender encoder (if included)
├── onehot_encoder_geo.pkl     # Geography encoder (if included)
└── README.md                  # Project documentation
```

*Note: Update the filenames in this structure to match the actual files in your repository.*

## 💻 Run Locally

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd ANN-Customer-Churn-Prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The application should open in your browser at:

`http://localhost:8501`

## 📊 Prediction Output

The application uses customer attributes as input and passes the processed features to the trained ANN model to predict the likelihood of customer churn.

The prediction depends on the model's output and the classification threshold configured in the application.

## 🎓 Learning Outcomes

Through this project, I practiced:

- Implementing an Artificial Neural Network for binary classification.
- Handling categorical and numerical features.
- Applying preprocessing consistently during inference.
- Integrating a trained deep learning model with Streamlit.
- Deploying a machine learning application for public access.

## 🔮 Future Improvements

- Add model evaluation metrics such as precision, recall, F1-score, and ROC-AUC.
- Display churn probability alongside the predicted class.
- Improve the interface with visual analytics.
- Add model explainability to understand the factors influencing predictions.
- Introduce monitoring and data validation for production use.

## 👨‍💻 Author

**MD Salman**

BCA Student | Aspiring Machine Learning Engineer

GitHub: [Add your GitHub profile URL]

## 📄 License

This project is intended for educational and learning purposes. Add a license file if you want to specify the terms under which others may use or modify the code.

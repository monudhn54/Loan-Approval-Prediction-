# 🏦 Loan Approval Prediction

A **Machine Learning-based Loan Approval Prediction System** that predicts whether a loan application is likely to be approved based on applicant information.

The project uses **Logistic Regression** for binary classification and provides an interactive **Streamlit web application** for real-time predictions.

---

## 🚀 Features

* Predicts loan approval eligibility using applicant details
* Binary classification using **Logistic Regression**
* Data preprocessing and feature engineering
* Feature scaling using **StandardScaler**
* Real-time predictions through a Streamlit interface
* Simple and user-friendly web UI
* Model evaluation using test accuracy

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** – Data manipulation and preprocessing
* **NumPy** – Numerical operations
* **Scikit-learn** – Machine Learning model and preprocessing
* **Logistic Regression** – Classification algorithm
* **StandardScaler** – Feature scaling
* **Streamlit** – Web application
* **Pickle** – Model serialization

---

## 📊 Machine Learning Workflow

The project follows the following pipeline:

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Train-Test Split
     ↓
Feature Scaling
(StandardScaler)
     ↓
Logistic Regression
     ↓
Model Evaluation
     ↓
Streamlit Web Application
     ↓
Real-Time Loan Prediction
```

---

## 🤖 Model

The project uses **Logistic Regression**, a supervised learning algorithm suitable for binary classification problems.

The model predicts two possible outcomes:

* ✅ **Loan Approved**
* ❌ **Loan Not Approved**

The dataset is preprocessed before training, including feature engineering and numerical feature scaling using `StandardScaler`.

### Model Performance

| Metric        |  Result |
| ------------- | ------: |
| Test Accuracy | **91%** |

> Accuracy is based on the test set used during model evaluation.

---

## 🌐 Streamlit Application

The trained model is integrated into a Streamlit web application.

Users can enter applicant information through the interface, and the application processes the input and generates a loan approval prediction in real time.

### Application Flow

```text
User Input
    ↓
Data Preprocessing
    ↓
Feature Scaling
    ↓
Trained Logistic Regression Model
    ↓
Prediction
    ↓
Loan Approval Result
```

---

## 📁 Project Structure

```text
Loan-Approval-Prediction/
│
├── app.py
├── loan_prediction_model.pkl
├── scaler.pkl
├── requirements.txt
├── dataset/
│   └── loan_data.csv
├── notebooks/
│   └── loan_prediction.ipynb
├── screenshots/
│   └── app.png
└── README.md
```

> Update the filenames above according to the actual files in your repository.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Loan-Approval-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Loan-Approval-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📦 Requirements

Example `requirements.txt`:

```text
pandas
numpy
scikit-learn
streamlit
```

---

## 💡 Example Prediction

The user provides applicant information such as:

* Applicant income
* Loan amount
* Credit history
* Education
* Employment status
* Property information
* Other relevant financial details

The model processes the information and returns the predicted loan eligibility.

---

## 🔮 Future Improvements

* Add additional classification models such as Random Forest, XGBoost, and SVM
* Compare multiple models using precision, recall, F1-score, and ROC-AUC
* Add probability-based prediction
* Improve UI/UX of the Streamlit application
* Add interactive data visualizations
* Deploy the application publicly
* Add model explainability using SHAP

---

## 👨‍💻 Author

**Monu Kumar**

Engineering Student | Electronics & Communication Engineering


---

## ⭐ Acknowledgements

This project was developed as part of my Machine Learning project work to explore **binary classification, data preprocessing, model training, and deployment using Streamlit**.

If you find this project useful, consider giving the repository a ⭐.

# Diabetes Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a patient has diabetes or not using Machine Learning techniques. The model was trained using medical diagnostic data and aims to assist in identifying potential diabetes cases based on patient health information.

The project includes:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature scaling
* Model training and evaluation
* Prediction results visualization

The implementation was completed using Python in a Jupyter Notebook environment.

---

## 📂 Project Structure

```bash
ML_Project_2_Diabetes_Prediction/
│
├── Diabetes_Prediction.ipynb     # Main Jupyter Notebook
├── README.md                     # Project documentation
└── diabetes.csv                     # Dataset file
```

---

## 🧠 Machine Learning Objective

The main objective of this project is to build a classification model capable of predicting diabetes based on medical attributes such as:

* Glucose Level
* Blood Pressure
* BMI
* Insulin
* Age
* Pregnancies
* Skin Thickness
* Diabetes Pedigree Function

The target variable determines whether the patient is diabetic or non-diabetic.

---

## 🛠️ Technologies & Libraries Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Dataset Information

The project uses the well-known **Pima Indians Diabetes Dataset**, which contains medical records for female patients and is commonly used for diabetes prediction tasks.

### Dataset Features

| Feature                  | Description                       |
| ------------------------ | --------------------------------- |
| Pregnancies              | Number of pregnancies             |
| Glucose                  | Plasma glucose concentration      |
| BloodPressure            | Diastolic blood pressure          |
| SkinThickness            | Triceps skin fold thickness       |
| Insulin                  | 2-Hour serum insulin              |
| BMI                      | Body Mass Index                   |
| DiabetesPedigreeFunction | Diabetes hereditary function      |
| Age                      | Patient age                       |
| Outcome                  | Diabetes result (0 = No, 1 = Yes) |

---

## 🔍 Project Workflow

### 1. Data Loading

The dataset was imported and inspected to understand its structure and quality.

### 2. Data Preprocessing

Several preprocessing steps were applied, including:

* Handling missing or zero values
* Data cleaning
* Feature scaling and normalization

### 3. Exploratory Data Analysis (EDA)

Visualization techniques were used to analyze:

* Feature distributions
* Correlations between variables
* Diabetes outcome patterns

### 4. Model Building

Machine Learning classification algorithms were trained to predict diabetes outcomes.

### 5. Model Evaluation

The models were evaluated using performance metrics such as:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📈 Results

The trained model successfully predicts whether a patient has diabetes based on health-related attributes. Different evaluation metrics were used to measure the model’s performance and effectiveness.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/HadeerAltabaa/ML_Project_2_Diabetes_Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd ML_Project_2_Diabetes_Prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```bash
Diabetes_Prediction.ipynb
```

---

## 📷 Project Highlights

* Real-world healthcare prediction problem
* Machine Learning classification workflow
* Data preprocessing and feature engineering
* Data visualization and analysis
* Model performance evaluation

---

## 🎯 Future Improvements

Possible future enhancements include:

* Hyperparameter tuning
* Trying additional ML algorithms
* Deploying the model as a web application
* Building an interactive prediction interface
* Improving model accuracy with advanced techniques

---

## 👩‍💻 Author

**Hadeer Al-Tabaa**  
Graduate of :**Arab Open University** with a Bachelor's degree in Computing with Business.

Interested in:
* Machine Learning
* Data Analytics
* Front-End Development
* Healthcare Technology Solutions

### GitHub Repository

[ML Project 2 - Diabetes Prediction Repository](https://github.com/HadeerAltabaa/ML_Project_2_Diabetes_Prediction/blob/main/Diabetes_Prediction.ipynb)

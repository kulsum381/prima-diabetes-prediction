# Prima Indians Diabetes Prediction using Logistic Regression

This project builds a logistic regression model to predict diabetes using the Pima Indians dataset.

## 📝 Overview

The main goal of this project is to:

- Train a **Logistic Regression** classifier on patient data
- Evaluate the model's performance using accuracy score
- Accept **real-time user input** for making predictions
- Determine whether a person is **Diabetic** or **Non-Diabetic**

---
## 📊 Dataset Description

The dataset includes 768 observations and 9 columns:

| Feature                    | Description                                                   |
|---------------------------|---------------------------------------------------------------|
| Pregnancies               | Number of pregnancies                                         |
| Glucose                   | Plasma glucose concentration a 2 hours in an oral glucose test|
| BloodPressure             | Diastolic blood pressure (mm Hg)                              |
| SkinThickness             | Triceps skin fold thickness (mm)                              |
| Insulin                   | 2-Hour serum insulin (mu U/ml)                                |
| BMI                       | Body Mass Index (weight in kg/(height in m)^2)                |
| DiabetesPedigreeFunction  | Function which scores likelihood of diabetes based on family history |
| Age                       | Age of the person (years)                                     |
| Outcome                   | 1 = Diabetic, 0 = Non-Diabetic                                |

📁 **Filename:** `diabetes.csv`

---
## ⚙️ Technologies Used

- **Python 3**
- **pandas** – Data handling
- **numpy** – Numerical operations
- **scikit-learn** – Machine learning (Logistic Regression, preprocessing, metrics)

## 💻 Setup & Installation

### 🔧 Prerequisites

Make sure Python and pip are installed. Then install the required packages:

```bash
pip install pandas numpy scikit-learn

## SAMPLE INPUT AND OUTPUT
![image](https://github.com/user-attachments/assets/f08b394c-e2a6-4af7-b2f3-c31279fcd395)

## 📈 Results
The model achieves around 75–80% accuracy depending on the dataset split.

Logistic Regression is ideal for binary classification tasks like this.

Feature scaling (StandardScaler) improves model performance and stability.

##👩‍💻 Author
Kulsum S.G
📫 Email: sgkulsum62@gmail.com
🎓 Cybersecurity and Data Analytics Enthusiast


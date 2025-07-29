# 🩺 Diabetes Risk Prediction

A machine learning project that predicts the risk of diabetes based on patient health data. The model is trained using imbalanced datasets and optimized using SMOTE for improved accuracy and fairness.

---

## 🔍 Overview

This project uses machine learning techniques to predict whether a patient is likely to develop diabetes based on health indicators such as BMI, glucose levels, blood pressure, and more. The dataset used is derived from medical records and exhibits class imbalance, which is handled using SMOTE.

The project compares multiple models including **Random Forest**, **SVM**, and **Logistic Regression**, with performance measured using accuracy, F1-score, precision, and recall.

---

## 🚀 Features

- ✅ Predicts diabetes risk using patient health data
- 📊 Balanced dataset using SMOTE to address class imbalance
- 🧠 Trained and compared multiple models: RF, SVM, Logistic Regression
- 📈 Evaluation using F1, precision, recall, and confusion matrix
- 📉 Visualizations of feature importance and model performance

---

## 🛠️ Tech Stack

| Tool / Library   | Purpose                                |
|------------------|----------------------------------------|
| Python           | Core programming language              |
| Scikit-learn     | ML algorithms and model evaluation     |
| SMOTE (imblearn) | Handling imbalanced classes            |
| Pandas, NumPy    | Data processing                        |
| Matplotlib, Seaborn | Visualization and plotting         |
| Jupyter Notebook | Interactive development and EDA        |

---

## 📁 Folder Structure

diabetes-risk-prediction/
│
├── data/
│ └── diabetes.csv # Health records dataset
│
├── notebooks/
│ └── Diabetes_Model.ipynb # Full analysis, training, evaluation
│
├── outputs/
│ └── plots/ # Confusion matrix, ROC, feature importance
│
├── requirements.txt # Python libraries needed
└── README.md # Project documentation


---

## 🧪 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/PrajwalShekar22/diabetes-risk-prediction.git
cd diabetes-risk-prediction

**2. Install dependencies**
bash
Copy
Edit
pip install -r requirements.txt

**3. Run the notebook**
bash
jupyter notebook notebooks/Diabetes_Model.ipynb

**📈 Model Results**
🔍 Best Model: Random Forest

🎯 Accuracy: 98%

🏆 F1 Score: 0.96

📊 SMOTE improved minority class recall from 68% to 93%

**📌 Use Cases**
Predictive screening for high-risk diabetic patients

Early detection support in clinical workflows

Health insurance risk modeling

**🚀 Future Enhancements**
Deploy as a web app (Flask or Streamlit)

Integrate with electronic medical records (EMR) systems

Enable real-time predictions via API

**📜 License**
This project is licensed under the MIT License.

**🙋‍♂️ Author**
Prajwal Gorkhar Chandrashekar
📧 prajwalshekar22@gmail.com
🔗 LinkedIn
🔗 GitHub

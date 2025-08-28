# 🫀 Heart Disease Prediction Toolkit

### 💡 Save Lives with AI — Predict Cardiovascular Risk Using Machine Learning

---

## 📌 Overview

This project is a complete **machine learning pipeline** designed to **predict the risk of heart disease** using clinical features. It includes:

- Data preprocessing & feature engineering  
- Training multiple ML models (Logistic Regression, Decision Tree, Random Forest)  
- Model evaluation (Accuracy, ROC-AUC, Classification Report, Confusion Matrix)  
- Deployment-ready **interactive UI using Gradio**  
- Compatibility with **Google Colab or local Python**

> ⚠️ Disclaimer: This tool is for **educational purposes only** and is **not** intended for clinical use.

---

## 📊 Features

| Feature                            | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| 🧠 ML Algorithms                   | Logistic Regression, Decision Tree, Random Forest                          |
| 📦 Data Handling                   | Synthetic or Kaggle dataset (UCI Heart Disease)                            |
| 🧼 Preprocessing                   | One-hot encoding, missing value handling, scaling                          |
| 📈 Evaluation                      | Accuracy, ROC-AUC, classification report, confusion matrix, ROC curves     |
| 🌐 Deployment                     | Interactive web UI with Gradio                                             |
| 🧰 Tools & Libraries               | `scikit-learn`, `pandas`, `gradio`, `matplotlib`, `joblib`, `seaborn`     |

---

## 🧑‍💻 Skills Demonstrated

- ✅ End-to-end supervised machine learning pipeline  
- ✅ Working with medical data & risk classification  
- ✅ Model explainability using ROC curves and feature importance  
- ✅ User interface design with **Gradio**  
- ✅ Deployment-ready code with model serialization (`joblib`)  
- ✅ Clean, modular, and reproducible pipeline

---

## 📂 Project Structure

heart-disease-predictor/
│
├── heart_disease_model.pkl # Saved ML model
├── heart_scaler.pkl # Saved feature scaler
├── feature_columns.pkl # Feature names for prediction alignment
├── main_notebook.ipynb # Google Colab / Jupyter Notebook (main)
├── README.md # Project documentation

yaml
Copy code

---

## 📥 Dataset

- Dataset: [UCI Heart Disease](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)  
- Format: CSV  
- Shape: 1000+ samples, 13 features  
- Labels: Binary (Disease / No Disease)

If the dataset is not available, a **synthetic dataset** is automatically generated for demonstration.

---

## 🧪 Example Input Fields

| Feature             | Description                         |
|---------------------|-------------------------------------|
| Age                 | Patient age                         |
| Sex                 | 0 = Female, 1 = Male                |
| Chest Pain Type     | 0 to 3                              |
| Cholesterol         | mg/dl                               |
| Fasting Blood Sugar | >120 mg/dl (0/1)                   |
| Resting ECG         | 0 = Normal, 1 = Abnormal, etc.     |
| Max Heart Rate      | beats per minute                   |
| Exercise Induced Angina | 0 = No, 1 = Yes               |
| ST Depression       | Float (0.0 to 6.0)                 |
| Thalassemia         | normal, fixed, reversible           |

---

## 💻 How to Run

### ✅ On Google Colab
1. Upload the notebook `main_notebook.ipynb` to Colab  
2. Run all cells from top to bottom  
3. Gradio interface will appear at the end with a shareable link

### 🖥️ Locally
```bash
# Step 1: Install dependencies
pip install pandas numpy scikit-learn gradio seaborn joblib matplotlib

# Step 2: Run the notebook or Python script
python your_script.py  # or run main_notebook.ipynb

# Step 3: The Gradio UI will launch in your browser
📈 Sample Results
Model	Accuracy	ROC-AUC
Logistic Regression	0.82	0.89
Random Forest	0.88	0.92
Decision Tree	0.84	0.86

(Results based on synthetic dataset)

📌 Use Cases
💼 Resume/Portfolio project for Data Science & ML roles

🏥 Medical risk prediction model for academic use

🎓 Final-year or bootcamp assignment

🧪 Practice on real-time ML + UI deployment

🔒 Disclaimer
This project is for educational purposes only and should not be used for real medical diagnoses. Always consult healthcare professionals.




Author : Anurag P.O.


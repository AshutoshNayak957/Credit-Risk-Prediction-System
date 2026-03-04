# 💳 Credit Risk Prediction System  
### AI-Powered Loan Default Risk Analysis

---

## 🚀 Project Overview

This project is a Machine Learning-based Credit Risk Prediction System that predicts the probability of a borrower defaulting on a loan.

It uses a Random Forest Classifier trained on financial data and provides an interactive, modern UI built with Gradio.

The system classifies applicants into:

- 🟢 LOW RISK  
- 🟠 MODERATE RISK  
- 🔴 HIGH RISK  

based on predicted probability of default.

---

## 🧠 Machine Learning Model

- Algorithm: Random Forest Classifier  
- Handles class imbalance using `class_weight='balanced'`  
- Stratified Train-Test Split  
- Performance Metrics:
  - Accuracy
  - Precision
  - ROC-AUC Score
  - Classification Report  

The trained model is saved using Joblib (`model.pkl`) for reuse.

---

## 📊 Features Used for Prediction

The model uses 10 financial indicators:

- Revolving Utilization of Unsecured Lines  
- Age  
- 30–59 Days Past Due  
- 60–89 Days Past Due  
- 90 Days Late  
- Debt Ratio  
- Monthly Income  
- Number of Open Credit Lines  
- Real Estate Loans  
- Number of Dependents  

---

## 🎨 User Interface Highlights

✔ Multi-tab Interface  
✔ Animated Gradient Background  
✔ Glassmorphism Design  
✔ Floating Visual Effects  
✔ Risk Probability Display Bar  
✔ Color-coded Risk Output  
✔ Feature Importance Visualization  

The UI is built using Gradio Blocks with custom CSS styling.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Gradio  
- Joblib  

---

## 📂 Project Structure

credit-risk-prediction/
│
├── app.py
├── model.pkl
├── requirements.txt
├── README.md
└── dataset files

---

## ⚙️ How to Run the Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/credit-risk-prediction.git
cd credit-risk-prediction
```

### 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Application

```bash
python app.py
```

The Gradio app will launch locally in your browser.

---

## 📈 Example Output

```
📌 Probability of Default: 72.45%
🏷 Risk Category: 🔴 HIGH RISK
```

Dynamic Risk Indicator:
- Green → Low Risk  
- Orange → Moderate Risk  
- Red → High Risk  

---

## 🔮 Future Improvements

- Deploy as a public web app  
- Add model comparison (XGBoost, LightGBM)  
- Add SHAP feature explanations  
- Improve dashboard analytics  

---

## 👨‍💻 Author

Ashutosh Nayak  
📧 ashutoshn957@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/ashutosh-nayak-2a8a04362  
💻 GitHub: https://github.com/AshutoshNayak957  

---

⭐ If you found this project useful, consider giving it a star!

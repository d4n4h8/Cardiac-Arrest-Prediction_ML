# 🫀 Cardiac Arrest Prediction System using Machine Learning

An AI-driven early warning system designed to predict the risk of cardiac arrest 10–30 minutes in advance by analyzing patient vital signs and time-series physiological data.

---

### 📌 Project Overview & Goal
Early detection of cardiac arrest is vital for patient survival in intensive care and emergency units. This project leverages Deep Learning architectures to process continuous time-series clinical metrics, identifying high-risk physiological patterns before clinical deterioration occurs. 

Our main goal is to support healthcare professionals with a reliable, interpretable early warning system to enhance patient safety.

---

### 📊 Dataset Notice
* **Data Type:** **Synthetic Dataset** (AI-Generated).
* **Generation Method:** The physiological data and patient vital signs used in this repository were synthetically generated to simulate clinical environments and time-series fluctuations.
  
---

### ⚙️ Core Features
* **Time-Series Deep Learning:** Utilizes Long Short-Term Memory (**LSTM**) networks to capture temporal dependencies in patient vital signs.
* **Explainable AI (XAI):** Integrated **SHAP (SHapley Additive exPlanations)** to provide feature importance maps, ensuring the model's clinical decisions are interpretable by medical experts.
* **Advanced Feature Engineering:** Robust preprocessing pipeline involving sequence segmentation, handling missing clinical values, and scale normalization.

---

### 📊 Model Performance & Results
The trained predictive model demonstrated outstanding robustness on clinical evaluation benchmarks:
* **📈 Accuracy:** `98.3%`
* **🎯 ROC AUC Score:** `0.999`

---

### 🛠️ Technologies & Libraries
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy">
</p>

* **XAI Framework:** `SHAP Tool`

---

### 🖼️ Example Output
![Example Output](Example%20Output.png)

---

### 💻 How to Run Locally

1. **Clone the repository:**
```bash
   git clone [https://github.com/d4n4h8/Cardiac-Arrest-Prediction.git](https://github.com/d4n4h8/Cardiac-Arrest-Prediction.git)
   cd Cardiac-Arrest-Prediction

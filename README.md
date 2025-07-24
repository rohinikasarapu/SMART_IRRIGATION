# 💧 Smart Irrigation System 🌱
### A Project Submitted on Behalf of AICTE

## 📘 Project Overview

The **Smart Irrigation System** is a machine learning-based solution designed to optimize water usage in agriculture. By analyzing key environmental parameters such as **soil moisture, temperature, and humidity**, the system predicts whether irrigation (pump activation) is necessary — helping farmers conserve water and increase crop efficiency.

This project was developed under the guidance of **AICTE** to promote sustainable and intelligent agricultural practices using technology.

---

## 📊 Features Implemented

- ✅ **Data Preprocessing:** Checked for null values and scaled features using `MinMaxScaler`  
- ✅ **Model Training:** Used `RandomForestClassifier` inside `MultiOutputClassifier` for multi-label prediction  
- ✅ **Evaluation:** Handled `classification_report` for each label individually to fix multi-output issues  
- ✅ **Model Saving:** Exported trained model as `.pkl` file for deployment  
- ✅ **Pump Activity Graphs:** Visualized pump ON/OFF status with respect to environmental conditions

---

## 📁 Files in This Project

| File Name                  | Description                                   |
|---------------------------|-----------------------------------------------|
| `Irrigation_System.ipynb` | Main Jupyter notebook with full pipeline      |
| `irrigation_machine.csv`  | Dataset used for training and testing         |
| `irrigation_model.pkl`    | Trained model saved for future predictions    |
| `README.md`               | Project documentation (this file)             |
| `pump_active_graph.png`   | Graph showing pump status trends (if plotted) |

---

## 🔧 Tools & Technologies

- **Language:** Python  
- **Libraries:** `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `joblib`  
- **Platform:** Jupyter Notebook  
- **Supported by:** AICTE (All India Council for Technical Education)

---

## 📈 Results & Impact

The system predicts irrigation requirements with high accuracy and provides visual insights on pump activity. It contributes to **smart farming** by reducing water wastage and promoting data-driven irrigation decisions.

---

## 📌 Future Enhancements

- Integrate with **IoT sensors** for real-time data collection  
- Use **XGBoost or LSTM** for better temporal predictions  
- Build a **mobile/web interface** for farmers to access suggestions easily

---

## 👩‍💻 Authors & Acknowledgements

Developed by: K.Rohini  
Supported by: **AICTE Smart India Project Initiative**

---


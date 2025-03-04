# 🔒 BESS-Set Cybersecurity Framework

## **📌 Overview**
The **BESS-Set Cybersecurity Framework** is a comprehensive system designed to enhance the security of **Battery Energy Storage Systems (BESS)**.  
It leverages **cutting-edge technologies and methodologies** to address cyber threats, enabling secure and efficient anomaly detection.

✅ **Advanced Machine Learning Models** → Detect anomalies with high accuracy  
✅ **SMOTE and PCA** → Handle imbalanced data and reduce dimensions  
✅ **Hybrid Encryption (AES + RSA)** → Ensure secure data transmission  
✅ **Real-World Attack Scenarios** → Address diverse cyber threats in BESS  

---

## **🔥 Features**
- ✅ **Binary and Multi-Class Classification** (High-Accuracy Models)  
- ✅ **Synthetic Data Balancing** (Using SMOTE)  
- ✅ **Dimensionality Reduction** (Using PCA)  
- ✅ **Hybrid Encryption for Data Security**  
- ✅ **Simulated Cyberattack Detection** (Data Tampering, Firmware Attacks)  
- ✅ **Comprehensive Security Metrics**  

---

## **📌 Dataset Description**
The **BESS-Set Dataset** provides time-series data for both normal operations and simulated cyberattacks in BESS environments.

| File Name                     | Description                                      |
|-------------------------------|--------------------------------------------------|
| `Training_Normal.csv`         | Normal operation data for model training.        |
| `Test_Normal.csv`             | Validation data for normal operations.          |
| `BadData_P_Exceeds.csv`       | Attack scenario: Active power exceeds limits.    |
| `BadData_Q_Exceeds.csv`       | Attack scenario: Reactive power exceeds limits.  |
| `BadData_P_Oscillations.csv`  | Attack scenario: Active power oscillations.      |
| `BadData_Q_Oscillations.csv`  | Attack scenario: Reactive power oscillations.    |
| `FalseData_P_Tampering.csv`   | Attack scenario: False active power readings.    |
| `FDI_BDI_SOC_Tampering.csv`   | Attack scenario: Battery SOC manipulation.       |
| `Firmware_Harmonics.csv`      | Attack scenario: Firmware causing harmonic distortion.|

**Key Parameters:**
- **Sampling Rate**: 1-second intervals.  
- **Features**: Active/Reactive Power, State of Charge (SOC), Voltage Levels, and Harmonic Distortions.  
- **Labels**: Binary attack labels (0: Normal, 1: Cyberattack).  

---

## **📌 Technologies Used**
- **Machine Learning Models:** Decision Tree, XGBoost, Random Forest  
- **Data Processing:** SMOTE, PCA  
- **Encryption Framework:** AES + RSA  
- **Programming Language:** Python  
- **Libraries:** Scikit-learn, Cryptography, Pandas, NumPy  

---

## **📌 Methodology**
### **1️⃣ Data Preparation**
- **SMOTE:** Balances dataset by generating synthetic minority samples.  
- **PCA:** Reduces dimensionality while preserving variance.

### **2️⃣ Machine Learning Models**
- **Binary Classification Models:**  
  - **Decision Tree:** Achieved 99.97% accuracy.  
  - **XGBoost:** High performance with 99.96% accuracy.  
- **Multi-Class Classification:**  
  - XGBoost demonstrated 99.82% accuracy.

### **3️⃣ Encryption Framework**
- **Hybrid Encryption (AES + RSA):**  
  - Ensures secure data handling and transmission.  
  - Combines AES for speed and RSA for robust key management.  

---



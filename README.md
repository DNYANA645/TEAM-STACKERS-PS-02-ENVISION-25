# ENVISION-2K26 | Team Stackers  
## PS-02: Heart Disease Risk Prediction

---

## 📌 Problem Statement
Heart disease is one of the leading causes of mortality worldwide.  
Early identification of individuals at high risk can significantly improve preventive healthcare and reduce fatal outcomes.

This project focuses on **Heart Disease Risk Prediction** under **Problem Statement PS-02**, with the aim of supporting **data-driven healthcare decisions**.

---

## 🎯 Project Objectives
- Address a real-world healthcare problem
- Collect and prepare original data
- Analyze key risk factors
- Build machine learning models for risk prediction
- Present insights using BI dashboards

---

## 🛣️ Workflow Overview (As per Poster)


### 1️⃣ Problem Definition
- Identified a real-world healthcare issue from PS-02
- Focused on heart disease as a critical medical condition
- Defined scope for risk prediction and preventive analysis

---

### 2️⃣ Data Collection & Understanding
Data collection was performed using a **hybrid approach**:

#### 🔹 Web Scraping (Reference-Based)
- Medical information such as:
  - Risk factors
  - Parameter ranges
  - Clinical thresholds  
- Extracted from trusted public medical sources

> ⚠️ No patient-level data was scraped or collected.

#### 🔹 Manual Data Generation
- Since real patient data is restricted due to privacy and ethical constraints:
  - A **synthetic raw dataset** was manually generated
  - Based on medically realistic ranges obtained from references
- This approach simulates real-world healthcare data while ensuring originality

Additionally:
- Features and target variable were identified
- All parameters were verified for medical relevance

---

### 3️⃣ Data Cleaning & Preprocessing
- Handled missing values and outliers
- Encoded categorical variables
- Scaled numerical features for ML readiness

---

### 4️⃣ Exploratory Data Analysis & Power BI Dashboard
- Analyzed trends and patterns related to heart disease
- Studied relationships between age, BP, cholesterol, heart rate, and risk
- Visualized insights using **Power BI dashboards**

---

### 5️⃣ Machine Learning Model Building & Evaluation
- Trained multiple ML models
- Compared performance using suitable metrics
- Selected the best accuracy-based and interpretable model

---

### 6️⃣ Model Deployment using Streamlit
- Deployed the trained model using **Streamlit**
- Enabled **real-time heart disease risk prediction**

---

## 📊 Dataset Description

### Dataset Type
- **RAW Dataset (Round-1 Submission)**

### Total Records
- **900 synthetic patient records**
--**16 COLUMNS**

### Parameters Included ( WE MAINLY FOCUSED ONLY ON THIS PARAMETERS)
- `age` – Age of patient  
- `sex` – Gender (0: Female, 1: Male)  
- `trtbps` – Resting blood pressure (mmHg)  
- `chol` – Serum cholesterol (mg/dL)  
- `thalach` – Maximum heart rate achieved  
- `exng` – Exercise-induced angina (0/1)  
- `output` – Heart disease risk (0: Low, 1: High)

---

## 🧠 Data Collection Methodology (Detailed)

Due to **ethical, legal, and privacy restrictions**, real patient-level healthcare datasets are not publicly accessible.  
Additionally, ENVISION-2K26 guidelines prohibit the use of pre-existing datasets.

### Therefore, our approach includes:
- Reference-based data understanding via web scraping
- Manual generation of synthetic patient records
- Distribution-matched expansion to maintain realism
- No usage of Kaggle or external datasets

This ensures:
- Originality
- Transparency
- Ethical compliance
- Rulebook adherence

---

## 📚 Medical References Used

> These sources were used **only for reference and range validation**, not for collecting patient data.

### 🔹 Mayo Clinic – Heart Disease & Risk Factors  
https://www.mayoclinic.org/diseases-conditions/heart-disease

### 🔹 Centers for Disease Control and Prevention (CDC)  
https://www.cdc.gov/heartdisease/risk_factors.htm

---

## 🛠️ Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Google Colab  
- Power BI  
- Streamlit  

---

## 🚀 Features in the Solution
- Real-time heart disease risk prediction
- Interactive Power BI dashboards
- Chatbot assistant (future scope)
- SOS / emergency support feature (future scope)

---

---

## ✅ Compliance Declaration
- No pre-existing datasets were used
- Data is synthetic and guideline-based
- Ethical and privacy-preserving approach followed
- Fully compliant with ENVISION-2K26 Datathon rules

---

## 👤 Team
**Team Stackers**  
Dnyanesh Shinde
ENVISION-2K26 Datathon

---

## 🏁 Final Note
This repository represents the **Round-1 submission**, including:
- Raw dataset
- Workflow poster
- Transparent documentation

Further rounds will build upon this foundation.


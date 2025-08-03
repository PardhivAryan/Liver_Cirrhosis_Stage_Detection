# 🩺 Liver Cirrhosis Stage Detection

This project focuses on detecting the stage of liver cirrhosis using patient health data. Using machine learning techniques, we aim to predict the histological stage of liver damage based on clinical and biochemical indicators.

---

## 📌 Objective

To develop a classification model that can predict the **stage of liver cirrhosis** (1, 2, or 3) using patient data collected from a clinical study.

---

## 🧾 Dataset Overview

The dataset originates from a **Mayo Clinic study on primary biliary cirrhosis (PBC)** of the liver conducted from 1974 to 1984. It includes data on demographics, symptoms, and laboratory results of patients.

---

### 🔑 Key Columns

| Column Name    | Description |
|----------------|-------------|
| `N_Days`       | Days from registration to endpoint (death, transplant, or study end) |
| `Status`       | Patient status: C (censored), CL (censored due to transplant), D (death) |
| `Drug`         | Treatment type: D-penicillamine or placebo |
| `Age`          | Age (in days) |
| `Sex`          | M (male), F (female) |
| `Ascites`      | Presence of ascites: Y (yes), N (no) |
| `Hepatomegaly` | Enlarged liver: Y (yes), N (no) |
| `Spiders`      | Spider angiomas: Y (yes), N (no) |
| `Edema`        | Edema status: N, S, or Y |
| `Bilirubin`    | Serum bilirubin (mg/dL) |
| `Cholesterol`  | Serum cholesterol (mg/dL) |
| `Albumin`      | Albumin (gm/dL) |
| `Copper`       | Urine copper (µg/day) |
| `Alk_Phos`     | Alkaline phosphatase (U/L) |
| `SGOT`         | Liver enzyme SGOT (U/mL) |
| `Tryglicerides`| Triglycerides (mg/dL) |
| `Platelets`    | Platelet count (/ml) |
| `Prothrombin`  | Prothrombin time (seconds) |
| `Stage`        | Histological stage of disease (1, 2, or 3) |

> 🔎 **Note**: Data includes both categorical and numerical features. Preprocessing was performed before modeling.

---

## 🛠️ Technologies Used

- **Python 3**
- **Google Colab / Jupyter Notebook**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`

---

## 📂 Project Structure

- 📓 `Liver_Cirrhosis.ipynb` — Code notebook  
- 📄 [Project Report (PDF)](https://github.com/PardhivAryan/Liver_Cirrhosis_Stage_Detection/blob/main/Liver%20Cirrhosis%20Stage%20Detection.pdf)  
- 📊 [Dataset (CSV)](https://raw.githubusercontent.com/PardhivAryan/Liver_Cirrhosis_Stage_Detection/refs/heads/main/liver_cirrhosis.csv)  
- 📘 `README.md` — Project overview

---

## 🚀 Getting Started

### ▶️ Open the Notebook
Click below to open and run the notebook directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D1THpMaUN_oPYRSdkBV8Ir9rmbUYHXWD)

---

### 💻 Run Locally
1. Clone the repository:
```bash
git clone https://github.com/PardhivAryan/liver-cirrhosis-stage-detection.git
cd liver-cirrhosis-stage-detection

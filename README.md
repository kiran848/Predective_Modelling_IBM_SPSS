# 🧠 Predictive Modelling of Lung Cancer Using IBM SPSS

This project aims to predict the likelihood of lung cancer in individuals based on various medical and lifestyle features. Using **IBM SPSS Statistics**, we performed data cleaning, exploratory data analysis, and predictive modeling to support early detection of lung cancer.

---

## 📁 Dataset Overview

- **Total Records**: 284  
- **Attributes**: 16 (including target)
- **Target Variable**: `LUNG_CANCER` (YES/NO)

### 🔶 Features:

| Feature               | Description                           |
|-----------------------|---------------------------------------|
| AGE                   | Age of the patient                    |
| GENDER                | Male / Female                         |
| SMOKING               | 1 = Yes, 0 = No                       |
| YELLOW_FINGERS        | Smoking symptom (Yes/No)              |
| ANXIETY               | Presence of anxiety                   |
| PEER_PRESSURE         | Peer influence towards smoking        |
| CHRONIC DISEASE       | Long-term illnesses                   |
| FATIGUE               | Feeling of tiredness                  |
| ALLERGY               | Presence of allergies                 |
| WHEEZING              | Shortness of breath while exhaling    |
| ALCOHOL CONSUMING     | Alcohol consumption habit             |
| COUGHING              | Persistent cough                      |
| SHORTNESS OF BREATH   | Difficulty in breathing               |
| SWALLOWING DIFFICULTY | Problems swallowing food              |
| CHEST PAIN            | Chest pain symptoms                   |
| LUNG_CANCER           | Target label (YES / NO)               |

---

## 🎯 Project Goals

- Clean and preprocess health survey data.
- Perform statistical and visual exploration.
- Build predictive models using:
  - Decision Trees (CHAID, CART)
  - Logistic Regression
- Evaluate models based on:
  - Accuracy
  - Confusion Matrix
  - ROC Curve / AUC
- Identify key features contributing to lung cancer prediction.

---

## ⚙️ Tools Used

- **IBM SPSS Statistics**
  - Frequencies, Crosstabs
  - Descriptive Statistics
  - Classification Models
  - ROC Analysis
- **Excel** (for minor cleaning and formatting)

---

## 📊 Sample Visuals

<p align="center">
  <img src="screenshots/correlation_matrix.png" width="500"/>
  <img src="screenshots/decision_tree.png" width="500"/>
  <img src="screenshots/roc_curve.png" width="500"/>
</p>

---

## 📝 Results

- **Best Model**: Decision Tree (CHAID)
- **Accuracy**: ~93%
- **Top Predictors**:
  - SMOKING
  - YELLOW_FINGERS
  - COUGHING
  - SHORTNESS OF BREATH
  - CHEST PAIN

These features showed the strongest association with the target class (`LUNG_CANCER`).

---
## 📝 Project flow

graph TD
    -A[Data Collection] --> B[Data Import into SPSS (.csv/.sav)]
    -B --> C[Data Cleaning & Preprocessing]
    -C --> D[Exploratory Data Analysis (EDA)]
    -D --> E[Feature Selection & Hypothesis Testing]
    -E --> F[Model Building in SPSS]
    -F --> G[Model Evaluation & Validation]
    -G --> H[Result Interpretation & Insights]
    -H --> I[Documentation & Reporting]
    
---

## 📌 Conclusion

This project demonstrates the application of IBM SPSS in health data analytics and predictive modeling. Through visual and statistical methods, we derived meaningful patterns to support early detection of lung cancer, potentially aiding healthcare professionals in decision-making.

---


## 🙋‍♀️ Contributors

- Kiran   
- Diksha Khangarot
- Anjali Sharma

---

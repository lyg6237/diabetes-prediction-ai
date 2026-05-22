# 🩸 Diabetes Prediction AI Project

> Machine Learning-based Diabetes Prediction using Health Data

---

## 📌 Overview

This project aims to predict diabetes using machine learning models based on patient health data.
By analyzing various health indicators such as glucose, BMI, blood pressure, and age, the model classifies whether a patient has diabetes or not.

---

## 🎯 Project Goals

* Analyze diabetes-related health data
* Perform data preprocessing and scaling
* Train machine learning classification models
* Compare model performance
* Interpret prediction results

---

## 🛠 Tech Stack

| Category             | Technologies                   |
| ---------------------| ----------------------------- |
| Language             | Python                          |
| Data Analysis        | Pandas, NumPy               |
| Visualization         | Matplotlib, Seaborn          |
| Machine Learning  | Scikit-learn                     |
| Environment         | Jupyter Notebook, Docker |
| Version Control     | GitHub                           |

---

## 📊 Dataset

### Pima Indians Diabetes Dataset

* Total Samples: 768
* Features: Glucose, BMI, BloodPressure, Insulin, Age, etc.
* Target: Diabetes Outcome (0 / 1)

| Feature           | Description              |
| ----------------- | ----------------------- |
| Glucose           | Blood glucose Level  |
| BloodPressure   | Blood pressure        |
| BMI                | Body Mass Index      |
| Insulin             | Insulin level            |
| Age                | Age                       |
| Outcome         | Diabetes 여부          |

---

## 🧹 Data Preprocessing

* Checked missing values
* Split feature / target data
* Applied train/test split (8:2)
* Used StandardScaler
* Replaced invalid 0 values with median values

### Processed Columns

* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI

---

## 🤖 Machine Learning Models

| Model                   | Accuracy |
| ---------------------- | ---------- |
| Logistic Regression  | 0.708      |
| Random Forest       | 0.779      |

> Random Forest showed better performance than Logistic Regression.

---

## 🏆 Best Model

### Random Forest

### Reason

* Higher Accuracy
* Strong performance on non-linear data
* Better feature relationship learning

---

## 📌 Confusion Matrix

```text
[[88 12]
 [22 32]]
```

| Actual / Predicted | 0 (Normal) | 1 (Diabetes) |
| -------------------- | ------------ | ------------- |
| 0 (Normal)           | 88            | 12             |
| 1 (Diabetes)         | 22            | 32             |
 
### Interpretation

* Correctly predicted most normal patients
* Correctly identified diabetic patients
* Some diabetic patients were incorrectly predicted as normal

> In medical AI, reducing False Negative cases is very important.

---

## 📈 Key Insights

* Glucose and BMI were important features
* Random Forest achieved the best performance
* Recall is important in medical prediction tasks
* Data preprocessing significantly affects model performance

---

## 🚀 Conclusion

This project implemented a machine learning-based diabetes prediction model using health-related data.
Among the tested models, Random Forest achieved the best performance.
The project also demonstrated the importance of preprocessing and evaluation metrics in medical AI systems.

---

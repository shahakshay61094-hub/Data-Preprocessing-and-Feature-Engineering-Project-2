# 📊 Data Preprocessing & Feature Engineering Project

## 🚀 Overview

This project focuses on **data preprocessing techniques** including handling missing values and outliers in a healthcare dataset.
The goal is to prepare raw data for machine learning by improving its quality and reliability.

---

## 🎯 Objectives

* Handle missing values using multiple imputation techniques
* Detect and treat outliers using statistical methods
* Compare different preprocessing techniques
* Generate a clean dataset suitable for machine learning

---

## 📁 Dataset

A **synthetic healthcare dataset** was generated with the following features:

* `patient_id` → Unique identifier
* `age` → Age of patient
* `gender` → Male/Female
* `region` → Geographic region
* `bmi` → Body Mass Index
* `blood_pressure` → Blood pressure level
* `cholesterol` → Cholesterol level
* `glucose` → Glucose level
* `disease_risk` → Target variable (0 = Low, 1 = High)

### ⚠️ Data Characteristics

* Includes **missing values (~10%)**
* Contains **outliers in numerical columns**
* Simulates real-world healthcare data

---

## 🛠️ Techniques Used

### 🔹 Missing Value Handling

* Simple Imputation (Mean)
* Most Frequent (Mode)
* Random Sampling + Missing Indicator
* KNN Imputation
* MICE (Multiple Imputation by Chained Equations)

---

### 🔹 Outlier Detection & Treatment

* Z-Score Method
* IQR (Interquartile Range)
* Percentile Capping
* Winsorization

---

## 📊 Final Approach

After comparing different techniques:

* **Best Imputation Method:** MICE
* **Best Outlier Method:** IQR

These methods provided better data consistency and preserved relationships between variables.

---

## 📂 Project Structure

```
📁 Project Folder
│── 📄 data_cleanser.ipynb        # Main notebook
│── 📄 health_data.csv            # Raw dataset
│── 📄 cleaned_health_data.csv    # Final cleaned dataset
│── 📄 README.md                  # Project documentation
```

---

## 📈 Output

* Cleaned dataset with:

  * No missing values
  * Reduced outliers
* Dataset ready for machine learning models

---

## 📌 Key Learnings

* Importance of handling missing values properly
* Impact of outliers on data analysis
* Comparison of different preprocessing techniques
* Real-world data cleaning workflow

---

## 🚀 Conclusion

Data preprocessing is a crucial step in any data science project.
This project demonstrates how different techniques can significantly improve data quality and prepare it for accurate modeling.

---

## 🙌 Author

**Herit**
(Data Science Enthusiast)

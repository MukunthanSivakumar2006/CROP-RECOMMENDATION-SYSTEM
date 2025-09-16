#  Week 2-Sustainable-Agriculture

## 🌱 AI-Powered Crop Recommendation System

## 📌 Project Overview

This project is developed as part of my **Edunet Foundation Internship (AICTE) under the theme Sustainable Agriculture**.
The aim is to build an AI-powered **Crop Recommendation System** that suggests the most suitable crop for cultivation based on soil nutrients and environmental conditions. By helping farmers make data-driven decisions, this project promotes sustainable farming practices, better yields, and optimized resource utilization.

---

## 🎯 Objectives

* Apply **Machine Learning (ML)** to recommend the best crop for given soil and climate conditions
* Analyze and preprocess agricultural datasets (nutrients, weather, soil parameters)
* Perform **EDA (Exploratory Data Analysis)** to understand data patterns and correlations
* Build a foundation for predictive modeling (Week 2) and deployment (Week 3)

---

## 📂 Dataset

* **Source**: Kaggle – Crop Recommendation Dataset
* **Size**: 2200 samples
* **Features**:

  * Soil Nutrients: N (Nitrogen), P (Phosphorus), K (Potassium)
  * Environmental: Temperature, Humidity, pH, Rainfall
* **Target**: Crop label (22 different crops)
* **Preprocessing**:

  * Checked missing values → **None**
  * Normalization using `StandardScaler`
  * Crop labels encoded with `LabelEncoder`
  * Final dataset saved as `preprocessed_crop_data.csv`

---

## ⚙️ Tech Stack

* **Programming Language**: Python
* **Libraries/Frameworks**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Platform**: Jupyter Notebook / Google Colab

---

## 🛠️ Workflow – Week 1

* **Data Collection**: Gathered dataset from Kaggle
* **Data Preprocessing**: Cleaned dataset, normalized features, encoded crop labels
* **Exploratory Data Analysis (EDA)**:

  * Feature distribution plots (histograms)
  * Correlation heatmap
* **Train-Test Split**: Prepared for ML modeling (1760 train, 440 test samples)

---

## 📊 Results (Week 1)

* ✅ Dataset ready for ML model training
* ✅ Preprocessed features & encoded labels
* ✅ Insights from EDA for better understanding of feature importance
* ✅ Balanced dataset (100 samples per crop class)

---

## 🌍 Sustainable Agriculture Impact

* Helps farmers select **optimal crops** based on soil and climate conditions
* Promotes **efficient resource utilization** (fertilizer, water)
* Supports **eco-friendly and sustainable farming** practices
* Encourages **data-driven decision making** in agriculture

---

## 📌 Future Enhancements (Next Weeks)

* **Week 2**: Train ML models (Decision Tree, Random Forest, Naïve Bayes, Logistic Regression) and evaluate performance
* **Week 3**: Build a user-friendly app (Streamlit/Flask) for real-time crop prediction with documentation & presentation

---

## 👨‍💻 Author

**Mukunthan S**

Internship: **Edunet Foundation Internship (AICTE)**

Theme: **Sustainable Agriculture**

---



# Task 01 – Predicting Weather Delay Case (WDCase)

### 🎯 Objective
Build a binary classification model using a Deep Neural Network (DNN) to predict the `WDCase` — whether a flight experienced a weather-related delay — based on flight-related features.

---

### 🧠 Dataset Overview

- **Rows:** 317,261  
- **Target:** `WDCase` (0 or 1)  
- **Features:**  
  - Time: `year`, `month`  
  - Airline info: `carrier`, `carrier_name`  
  - Airport info: `airport`, `airport_name`  
  - Delay-related features: `carrier_ct`, `weather_ct`, `nas_ct`, etc.

---

### 🛠 Tools & Libraries

- Python 3.x  
- TensorFlow / Keras  
- scikit-learn  
- pandas, numpy, matplotlib

---

### 📊 Model Performance

- **Model Type:** Dense Neural Network  
- **Evaluation Metric:** Confusion Matrix  
- **Confusion Matrix:**
  ```
  [[42915    32]
   [   18 20488]]
  ```
- **Interpretation:**
  - True Negatives (TN): 42,915
  - False Positives (FP): 32
  - False Negatives (FN): 18
  - True Positives (TP): 20,488

- Very low false negatives and positives — indicating high precision and recall.

---

### 📁 Files

- `DL_lec2.ipynb`: Notebook with data preparation, modeling, training, and evaluation.
- `KerasModel.keras`: Saved model.
- `data.csv`: Dataset used for training/testing.

---

### ✅ Key Learnings

- How to preprocess structured data for DNN input.
- Training a binary classifier using Keras.
- Evaluating classification with a confusion matrix.

---

> This is part of the full [Deep Learning Practical Tasks](../README.md) series.

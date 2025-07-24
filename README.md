
# ✈️ Predicting Flight Delays Using Classification Techniques

This project focuses on predicting whether a flight will be delayed using classification algorithms such as **Logistic Regression** and **XGBoost (Gradient Boosting)**. The dataset includes flight schedules, routes, and other attributes to help build a predictive model.

---

## 📊 Exploratory Data Analysis

We began with a thorough EDA to understand patterns in delays across airlines and routes.

### 🛬 Which flight has the most delays?

![Most Delayed Flights](https://github.com/user-attachments/assets/3b233b0b-8413-4e65-8c99-87ad6704b709)

---

### 🛫 Which flight had the most on-time or no delays?

![Most On-Time Flights](https://github.com/user-attachments/assets/d02165d7-34fe-4d33-a363-19b345312d64)

---

### 🔝 Top 20 Flight Routes with the Most Delays

![Top Routes with Delays](https://github.com/user-attachments/assets/1a6cd5da-0361-4a8b-9aec-057d1ffbf931)

---

## 🤖 Model Performance

### ✅ Logistic Regression

* **Accuracy:** 0.726
* **Classification Report:**

```
              precision    recall  f1-score   support

           0       0.73      1.00      0.84    845201
           1       0.50      0.01      0.02    318615

    accuracy                           0.73   1163816
   macro avg       0.61      0.50      0.43   1163816
weighted avg       0.66      0.73      0.62   1163816
```

#### Confusion Matrix:

![Confusion Matrix - Logistic Regression](https://github.com/user-attachments/assets/8dec65a5-5bf9-46ae-977b-192ab750d099)

---

### 🌲 XGBoost Classifier

* **Accuracy:** 0.737
* **Classification Report:**

```
              precision    recall  f1-score   support

           0       0.74      0.98      0.84    845201
           1       0.63      0.10      0.17    318615

    accuracy                           0.74   1163816
   macro avg       0.69      0.54      0.51   1163816
weighted avg       0.71      0.74      0.66   1163816
```

---

## 📌 Key Insights

* Flights with **no delay** are far more common than delayed ones, creating a class imbalance challenge.
* **Logistic Regression** performed reasonably but struggled with recall for delayed flights.
* **XGBoost** improved performance slightly, especially in identifying delayed flights, though recall remains low due to class imbalance.



#  Species Classification Using Machine Learning  

This repository contains code, datasets, and experiments for classifying plant species using machine learning models. The project explores various modeling techniques, including Random Forest (RF), Gradient Boosting, and a Heterogeneous Stacked Model, to classify species based on spectral data.


##  Project Overview  

### **1️⃣ ML Model Training on Dataset**  
- Trains multiple machine learning models (**Random Forest, Gradient Boosting, Stacked Model**).
- Evaluates models using **F1-score, accuracy, and other metrics**.
- Handles **class imbalance** using weighting techniques.

### **2️⃣ Site-Specific Train-Test Experiment**  
- Tests model generalization across different ecological sites.
- Evaluates accuracy and **F1-score across sites** to analyze performance.
- Identifies challenges in specific sites with low model accuracy.

### **3️⃣ RGB vs. Multispectral Experiment**  
- Compares **RGB-only vs. multispectral** feature importance.
- Analyzes how **different spectral bands** impact classification performance.

---

## Results & Insights  

 **In at least 5 sites, one of the models achieved ≥ 73% F1-score.**  
 **In 4 sites, models achieved ≥ 60% F1-score, indicating moderate accuracy.**  
 **However, 3 sites had performance drop-offs (≤ 22% F1-score).**  
 **For 2 sites, no model achieved even 1% F1-score, highlighting domain shift challenges.**  

 These findings encourage further investigation into **feature engineering, data augmentation, and model improvements**.

---

## 🛠️ Setup & Installation  

### **Prerequisites**  
Ensure you have **Python 3.8.8** installed along with the required libraries:  

```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn plotly



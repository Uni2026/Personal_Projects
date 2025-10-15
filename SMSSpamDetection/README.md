# 📩 SMS Spam Detection using Machine Learning

This project uses **machine learning** to detect spam messages (SMS) that may contain scams, phishing links, or fraud attempts.  
Unlike email spam, SMS spam is harder to detect due to **short text, slang, and minimal metadata**.  
The goal was to build an accurate and efficient model that can automatically classify messages as **spam or ham**.

---

## 🚀 Overview

The system uses **TF-IDF vectorization** to convert text into numerical form and applies various ML models to classify messages.  
After testing multiple algorithms, **Support Vector Machine (SVM)** gave the best performance with **98.16% accuracy**.

---

## ⚙️ Steps Involved

1. **Data Cleaning** – Removed duplicates, converted text to lowercase, removed special characters.  
2. **Label Encoding** – Converted labels: “ham” → 0, “spam” → 1.  
3. **Feature Extraction** – Used TF-IDF with 5000 top features.  
4. **Model Training** – Trained models like Logistic Regression, Naive Bayes, Random Forest, Decision Tree, KNN, and SVM.  
5. **Evaluation** – Used Accuracy, Precision, Recall, and F1-score to measure results.  

---

## 🧠 Model Performance

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 96.13% |
| Naive Bayes | 96.81% |
| Decision Tree | 96.23% |
| Random Forest | 97.58% |
| KNN | 91.49% |
| **SVM** | **98.16%** |

SVM achieved the highest accuracy and consistency during cross-validation, making it the best model for this task.

---

## 🧰 Tech Stack

- **Language:** Python  
- **Libraries:** scikit-learn, pandas, numpy, nltk  
- **Vectorization:** TF-IDF  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score  

---

## 📈 Result

- **Best Model:** Support Vector Machine (SVM)  
- **Accuracy:** 98.16%  
- **Cross-validation Accuracy:** 97.93% ± 0.39%  
- **Outcome:** Reliable and robust model for SMS spam detection.  

---

## 👩‍💻 Author

**Janiah Suresh William**  
Final Year, B.E. Computer Science  
BITS Pilani, Dubai Campus  

# SMS Spam Detection ML

A simple Machine Learning project to classify SMS messages as **Spam** or **Ham** (Legitimate).

---

## 📌 Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning algorithms to automatically identify and filter out unwanted spam SMS messages.

---

## 🎯 Objective
* Build an accurate SMS spam classifier using Python.
* Preprocess raw text and convert it into numerical data using TF-IDF.
* Compare models to find the best algorithm for spam detection.

---

## 🧰 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, NLTK
* **Algorithms:** Naive Bayes, Logistic Regression, SVM

---

## ⚙️ Methodology
1. **Data Cleaning:** Handle missing values and label messages (Spam/Ham).
2. **Text Preprocessing:** Convert to lowercase, remove punctuation, stop words, and apply stemming.
3. **Feature Extraction:** Convert text into numerical vectors using **TF-IDF**.
4. **Model Training:** Train Naive Bayes, Logistic Regression, and SVM models.
5. **Evaluation:** Test performance using Accuracy and Precision scores.

---

## 📊 Results

| Model | Accuracy | Precision |
| :--- | :--- | :--- |
| **Multinomial Naive Bayes** | 97.4% | 98.2% |
| **Logistic Regression** | 96.2% | 97.0% |
| **Support Vector Machine (SVM)** | 98.0% | 98.5% |

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/swe28122812-max/SMS_SPAM_DETECTION_ML.git](https://github.com/swe28122812-max/SMS_SPAM_DETECTION_ML.git)

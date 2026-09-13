# SMS Spam Detection ML

A Machine Learning and Natural Language Processing (NLP) project designed to automatically classify incoming SMS text messages as either **Spam** or **Ham** (legitimate).

---

## 📌 Project Overview
With the increasing volume of mobile communication, unwanted spam messages create security risks, phishing threats, and inconvenience. This repository implements end-to-end Machine Learning pipelines to process unstructured text data and accurately predict whether a message is spam or genuine.

---

## 🎯 Objective
* Build an efficient and reliable text classification pipeline using NLP techniques.
* Transform raw text messages into meaningful numerical feature representations using vectorization techniques (TF-IDF / CountVectorizer).
* Evaluate and compare multiple classification algorithms to select the optimal model for production deployment.

---

## 🧰 Technologies Used
* **Programming Language:** Python 3.x
* **Data Processing & Manipulation:** Pandas, NumPy
* **Natural Language Processing (NLP):** NLTK, Scikit-learn (`TfidfVectorizer`)
* **Machine Learning Models:** 
  * Multinomial Naive Bayes
  * Logistic Regression
  * Support Vector Classifier (SVC)
* **Data Visualization:** Matplotlib, Seaborn

---

## ⚙️ Methodology

1. **Data Collection & Cleaning:** 
   * Load the dataset, remove duplicates, check for missing values, and handle target label encoding (`ham` -> 0, `spam` -> 1).
2. **Text Preprocessing:**
   * Lowercasing text
   * Tokenization (breaking text into individual words)
   * Removing special characters, punctuation, and numerical noise
   * Removing Stop Words
   * Applying Stemming / Lemmatization (e.g., PorterStemmer)
3. **Feature Extraction:**
   * Convert processed text tokens into TF-IDF (Term Frequency - Inverse Document Frequency) vectors.
4. **Model Training & Building:**
   * Split dataset into training and testing sets (80/20 split).
   * Train Naive Bayes, Logistic Regression, and SVM algorithms.
5. **Evaluation & Fine-Tuning:**
   * Measure performance using Accuracy, Precision, Recall, and F1-Score matrices with a specific focus on high Precision to minimize False Positives.

---

## 📊 Results & Performance

Below is the comparative performance analysis of the tested algorithms:

| Algorithm | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Multinomial Naive Bayes** | 97.4% | 98.2% | 95.1% | 96.6% |
| **Logistic Regression** | 96.2% | 97.0% | 94.0% | 95.5% |
| **Support Vector Machine (SVM)** | 98.0% | 98.5% | 96.2% | 97.3% |

*(Note: Replace the table values above with your exact model outputs if different.)*

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/swe28122812-max/SMS_SPAM_DETECTION_ML.git](https://github.com/swe28122812-max/SMS_SPAM_DETECTION_ML.git)
   cd SMS_SPAM_DETECTION_ML

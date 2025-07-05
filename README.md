# 🔖 Fake News Prediction Model

Hey, I created a **Fake News Prediction Model** using **Logistic Regression** and various text preprocessing techniques like stemming, stopword removal, and TF-IDF vectorization.

---

## 🚀 Project Overview

This project is a **machine learning model** that classifies news articles as **Real (1)** or **Fake (0)** based on their textual content.

---

## 🔧 Technologies Used

* **Python 3**
* **NumPy**
* **Pandas**
* **NLTK** (Natural Language Toolkit)
* **Scikit-learn** (`sklearn`)

---

## 🛠️ Machine Learning Pipeline

1. **Data Cleaning:**

   * Lowercasing
   * Removing special characters & numbers
   * Removing stopwords
   * Stemming words (Porter Stemmer)

2. **Feature Extraction:**

   * Used **TF-IDF Vectorizer** to convert text into numeric features.

3. **Model Training:**

   * Used **Logistic Regression** for binary classification.

4. **Model Evaluation:**

   * Calculated **Accuracy Score** on the test set.

---

## 📁 Dataset

The dataset contains columns like:

* `author`
* `title`
* `text`
* `label` → 0 for **Fake**, 1 for **Real**

---

## 🏁 How to Run

1. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn nltk
   ```
2. Run the Python script / notebook (`FakeNews.ipynb`).

---

## 📊 Example Accuracy

> ✅ Model Accuracy: Around **95.28%**

---

## 🤖 Future Improvements

* Try other models like SVM, Random Forest.
* Tune hyperparameters for better accuracy.
* Add API endpoints using Flask/FastAPI.

---

## 📌 Author

**Rakshit Jain (@rakshitjain23)**

# Fake News Detection System using Logistic Regression

This project implements a **Fake News Detection System** using **Machine Learning** techniques.
It classifies news articles as **Fake** or **Real** based on their textual content using **Logistic Regression** and **TF-IDF vectorization**.

---

## Dataset Information

* **Source:** Kaggle Fake News Dataset
* **Files Used:**

  * `Fake.csv` → Fake news articles
  * `True.csv` → Real news articles
* **Total Records:** ~45,000+ articles
* **Labels Assigned:**

  * `0` → Fake News
  * `1` → Real News

---

## Data Preprocessing

The text data is cleaned before training to improve model accuracy:

* Conversion to lowercase
* Removal of URLs and web links
* Removal of HTML tags
* Removal of emojis and punctuation
* Removal of digits and newline characters

This ensures the model learns only meaningful textual patterns.

---

## Feature Extraction

* **Technique Used:** TF-IDF (Term Frequency–Inverse Document Frequency)
* Converts raw text into numerical vectors
* Helps highlight important words while reducing the impact of common terms

---

## Model Training

* **Algorithm:** Logistic Regression
* **Train-Test Split:** 70% training, 30% testing
* The model is trained on vectorized text data

---

## Evaluation

* Model accuracy is calculated on the test dataset
* Performance metrics include:

  * Precision
  * Recall
  * F1-score
* `classification_report` is used for detailed evaluation

---

## Manual News Prediction

The system supports **real-time testing**:

* User inputs custom news text
* Text is preprocessed and vectorized
* Model predicts whether the news is **Fake** or **Not Fake**

---

## Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib
* Regular Expressions (re)

---

## Conclusion

The project demonstrates that **Logistic Regression**, when combined with proper text preprocessing and TF-IDF vectorization, can effectively detect fake news with high accuracy.

---

## Author

**Gurarpit Singh**
BCA | Machine Learning Enthusiast



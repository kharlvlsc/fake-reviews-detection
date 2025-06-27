Here’s a cleaned-up, professional, and well-structured version of your README file that keeps your content intact while improving grammar, clarity, and formatting:

---

# Fake Reviews Detection

## Problem Statement

The goal of this project is to detect fake product reviews from a large dataset containing reviews across various categories. Each review is associated with:

* A product rating,
* A label (`0` for *Genuine* reviews or `1` for *Potentially Fraudulent* human-written reviews),
* And the review text itself.

A review is considered **potentially fraudulent** if it is labeled as potentially fraudulent `1`; otherwise, it is considered **genuine** (`0`).

---

## Dataset Description

This dataset consists of:

* **50** genuine product reviews
* **50** potentially fraudulent product reviews

Label definitions:

* `0` = Genuine Reviews (authentic, human-written)
* `1` = Potentially Fraudulent (synthetic, fake)

---

## 🛠️ Python Libraries and Packages Used

* `numpy`
* `pandas`
* `matplotlib.pyplot`
* `seaborn`
* `warnings`
* `nltk`, `nltk.corpus`
* `string`
* `sklearn.naive_bayes`
* `sklearn.feature_extraction`
* `sklearn.model_selection`
* `sklearn.ensemble`
* `sklearn.tree`
* `sklearn.linear_model`
* `sklearn.svm` (`svc`)
* `sklearn.neighbors`

---

## Text Preprocessing Techniques

* Removing punctuation characters
* Converting text to lowercase
* Eliminating stopwords
* Stemming
* Lemmatizing
* Removing digits

---

## Transformers Used for Text Vectorization and Normalization

* **CountVectorizer** (Bag of Words Model)
* **TF-IDF** (Term Frequency-Inverse Document Frequency)

---

## Machine Learning Algorithms Used

* Multinomial Naive Bayes

---

## Performance Overview of ML Models
* **CLASSIFICATION REPORT ** 
| Metric / Class        | Precision | Recall | F1-Score | Support |
| --------------------- | --------- | ------ | -------- | ------- |
| **Class 0** (Genuine) | 0.71      | 0.71   | 0.71     | 17      |
| **Class 1** (Fake)    | 0.72      | 0.72   | 0.72     | 18      |
| **Macro Average**     | 0.71      | 0.71   | 0.71     | 35      |
| **Weighted Average**  | 0.71      | 0.71   | 0.71     | 35      |

* **ACCURACY**
| Metric                        | Value      |
| ----------------------------- | ---------- |
| **Accuracy Score**            | 0.7143     |
| **Model Prediction Accuracy** | **71.43%** |

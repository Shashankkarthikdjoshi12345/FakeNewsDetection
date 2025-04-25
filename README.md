# 📰 Fake News Detection

This project aims to detect fake news in real-time using a machine learning model based on the **Passive Aggressive Classifier**. It leverages text processing and classification techniques to distinguish between real and fake news articles.

---

## 🚀 Project Overview

In an age of rapidly spreading misinformation, this project demonstrates how machine learning can be used to classify news articles as **FAKE** or **REAL** using natural language processing (NLP).

The core components of this project include:
- Text vectorization using **TF-IDF**
- Classification using **PassiveAggressiveClassifier**
- Evaluation using metrics like **Accuracy**, **Precision**, **Recall**
- (Optional) Visualizing classified articles using **PCA or t-SNE**

---

## 🛠 Tech Stack

- **Python 3.x**
- **scikit-learn** – ML algorithms & evaluation
- **Pandas / NumPy** – Data manipulation
- **Matplotlib** – Visualization
- **TfidfVectorizer** – Feature extraction from text
- **PassiveAggressiveClassifier** – Efficient classifier for high-dimensional data

---

## 📦 Dataset

The project uses the `fake_or_real_news.csv.csv` dataset, which contains labeled news articles.

| Column | Description     |
|--------|-----------------|
| text   | News content    |
| label  | FAKE or REAL    |

You can download the dataset (https://www.kaggle.com/code/meetnagadia/fakenewsdetection-passiveaggressiveclassifier/input)

---

## 🧪 Model Training Steps

1. Load and clean the dataset
2. Split the data into train/test sets
3. Vectorize text using **TfidfVectorizer**
4. Train a **PassiveAggressiveClassifier**
5. Evaluate the model (accuracy, precision, recall)
6. Visualize classified results (optional)

---

## 📊 Sample Results

```python
Accuracy: 92.9%
Precision (FAKE): 93%
Recall (FAKE): 93%

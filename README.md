# 📰 Fake News Detection using Machine Learning

This project focuses on detecting **fake news** using various machine learning algorithms. With the rising spread of misinformation, especially through online media, this solution aims to automatically identify misleading or false articles using text classification techniques.

---

## 📌 Overview

We used a publicly available dataset from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset), which contains two separate files:

- `Fake.csv` — Articles flagged as fake
- `True.csv` — Articles labeled as real

These were combined and preprocessed for binary classification.

---

## 🚀 Features

- Text preprocessing (removing punctuation, stop words, tokenization)
- TF-IDF vectorization for text representation
- Comparison of **5 ML classifiers**:
  - Naive Bayes
  - Random Forest
  - Decision Tree
  - Support Vector Machine (SVM)
  - Logistic Regression
- Accuracy and performance evaluation
- Clean modular code with reproducible results

---

## 📁 Dataset

Dataset used: [Fake and Real News Dataset – Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Archi-Bachani/Fake_News_Detection_Model.git
   cd Fake_News_Detection_Model

   ```

2. Install Dependencies:

    ```bash
    pip install -r requirements.txt

    ```

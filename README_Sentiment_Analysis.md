# 🧠 Sentiment Analysis using Machine Learning and NLP

## 📌 Project Overview

This project aims to build a **Sentiment Analysis** model that classifies text data into **positive**, **neutral**, or **negative** sentiments. It leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to analyze and interpret the emotional tone behind textual inputs such as customer feedback, product reviews, or social media posts.

---

## 📁 Dataset Description

- **Features**: 
  - `clean_text`: Preprocessed text data
  - `category`: Sentiment label (`-1 = Negative`, `0 = Neutral`, `1 = Positive`)
- The dataset used is already cleaned, tokenized, and ready for vectorization.

---

## ⚙️ Technologies & Libraries Used

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Model building and evaluation
  - `nltk` – Text preprocessing
  - `wordcloud` – Optional visualization

---

## 🔍 Key Concepts Covered

- **Text Cleaning & Preprocessing**
- **TF-IDF Vectorization**
- **Naive Bayes Classifier**
- **Model Evaluation (Accuracy, Precision, Recall, F1-score)**
- **Confusion Matrix & Feature Importance**
- **Custom Sentiment Prediction Function**
- **(Optional) Word Cloud Visualization**

---

## 📈 Model Performance

- **Accuracy**: `73.7%`
- **Macro Avg F1-Score**: `0.70`
- **Weighted Avg F1-Score**: `0.72`

| Sentiment | Precision | Recall | F1-Score |
|-----------|-----------|--------|----------|
| Negative (-1) | 0.91 | 0.42 | 0.57 |
| Neutral (0)   | 0.88 | 0.67 | 0.76 |
| Positive (1)  | 0.65 | 0.95 | 0.78 |

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis
   cd sentiment-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook to train and evaluate the model.

---

## 📬 Contact

For questions or collaborations, reach out to [your-email@example.com]

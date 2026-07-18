# 📰 AI Fake News Detector

An AI-powered Fake News Detection system built using **Machine Learning** and **Generative AI**. The project classifies news articles as **Real** or **Fake** using a Logistic Regression model and provides an AI-generated explanation and summary of the news.

---

## 📌 Features

- ✅ Detects whether a news article is **Real** or **Fake**
- ✅ Uses **TF-IDF Vectorization** for text preprocessing
- ✅ Machine Learning classification using **Logistic Regression**
- ✅ Generates a **summary** of the news article using a pre-trained Transformer model
- ✅ Provides a simple explanation of why the news may be fake

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Hugging Face Transformers
- Google Colab / Jupyter Notebook

---

## 🤖 Machine Learning Model

**Classifier:** Logistic Regression

### Workflow

1. Load the dataset
2. Preprocess the text data
3. Convert text into numerical features using **TF-IDF Vectorizer**
4. Train a **Logistic Regression** model
5. Predict whether the news is Fake or Real
6. Generate a summary using a Transformer model
7. Explain why the article may be fake using simple heuristics

---

## 🧠 Generative AI Model

This project uses the following Hugging Face model:

**Model:** `sshleifer/distilbart-cnn-12-6`

Purpose:
- Summarizes long news articles into shorter readable summaries.

---

## 📂 Project Structure

```
AI-Fake-News-Detector/
│
├── AIFakeNewsDetetctor.ipynb
├── README.md
└── requirements.txt (optional)
```

---

## 📦 Required Libraries

Install the required packages using:

```bash
pip install pandas numpy scikit-learn transformers accelerate sentencepiece
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Fake-News-Detector.git
```

2. Open the notebook in Jupyter Notebook or Google Colab.

3. Install the required libraries.

4. Run all cells.

5. Enter a news article to check whether it is **Real** or **Fake**.

---

## 📊 Machine Learning Pipeline

```
News Article
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Logistic Regression
      │
      ▼
Prediction
      │
      ├── Fake / Real
      ├── AI Summary
      └── Explanation
```

---

## 📈 Future Improvements

- Train on a larger real-world dataset
- Improve prediction accuracy using advanced models
- Build a web application using Flask or Streamlit
- Integrate Google Gemini or OpenAI for better explanations
- Deploy the project on Render or Hugging Face Spaces

---

## 👨‍💻 Author

**Sahil Dubey**

B.Tech Student | Machine Learning & Generative AI Enthusiast

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub to support the project.

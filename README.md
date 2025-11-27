# 🎬 Sentiment Analysis on IMDB Movie Reviews (LSTM Deep Learning)

This project performs binary sentiment classification (Positive/Negative) on the IMDB Movie Review dataset using **Natural Language Processing (NLP)** and a **Long Short-Term Memory (LSTM)** neural network.
The goal of this project is to build a clean, reproducible, and easy-to-understand sentiment analysis pipeline that demonstrates skills in preprocessing, modeling, evaluation, and inference.

---

## 📘 Project Highlights

- Full preprocessing pipeline  
- Cleaned and normalized text  
- Tokenization & sequence padding  
- Deep learning model using LSTM  
- Model evaluation (accuracy, F1-score, confusion matrix)  
- Predict sentiment for new reviews  
- Beginner-friendly but industry-style project structure  

---

## 📂 Dataset

**Dataset:** IMDB Movie Reviews Dataset  
**Source:** Kaggle  
**Size:** 50,000 movie reviews  

Each entry has:

| Column     | Description                         |
|------------|-------------------------------------|
| review     | The raw text of the movie review    |
| sentiment  | "positive" or "negative"            |

---

## 🧹 Preprocessing

The text undergoes several preprocessing steps:

- Remove HTML tags  
- Remove special characters  
- Convert to lowercase  
- Tokenize text  
- Convert tokens to sequences  
- Pad sequences to fixed length  
- Encode labels (0 = negative, 1 = positive)

---

## 🧠 Model Architecture (LSTM)

The model is built using **TensorFlow / Keras**:
**Optimizer:** Adam  
**Loss:** Binary Crossentropy  
**Metrics:** Accuracy  

This architecture is lightweight but powerful enough to extract information from sequential text data.

---

## 📊 Evaluation Metrics

The model is evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

You can find the evaluation results in the output of the `.fit()` and prediction steps.

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt

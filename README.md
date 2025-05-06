# Emotion Detection from Text

This project is a simple machine learning model that predicts the emotion behind a given piece of text. It uses natural language processing (NLP) techniques and a trained machine learning model to classify input text into emotional categories like `happy`, `sad`, etc.

## 🚀 Features

- Preprocessing with `neattext` to clean input text.
- Uses a vectorizer (CountVectorizer or TF-IDF) for text-to-numeric transformation.
- A trained machine learning classifier (`emotion_model.pkl`) to predict emotions.
- Lightweight, fast, and easy to use.

## 🧠 Technologies Used

- Python
- Google Colab
- scikit-learn
- neattext
- numpy
- joblib

## 📂 Project Structure

emotion-detection-text/
│
├── Emotion_Detector.ipynb # Main Colab notebook
├── emotion_model.pkl # Trained machine learning model
├── vectorizer.pkl # Text vectorizer used in training
└── README.md # Project documentation


## 🔍 How it Works

1. The input text is cleaned using `neattext`.
2. Stopwords and special characters are removed.
3. The cleaned text is converted into a numerical format using the saved `vectorizer.pkl`.
4. The emotion is predicted using the trained `emotion_model.pkl`.

## 🧪 Sample Output

```python
Text: I can't wait for the trip!
Predicted Emotion: happy

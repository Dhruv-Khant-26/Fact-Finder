# Fake News Detection

A Streamlit-based web application that uses machine learning to detect fake news articles. The app allows users to input news content through multiple methods and provides real-time predictions with confidence scores.

## Features

- **Multiple Input Methods**: Upload files (PDF, DOCX, TXT), paste text directly, or fetch from Google Drive
- **Real-time Detection**: Instant prediction using a trained ML model
- **User-friendly Interface**: Clean Streamlit UI with file previews
- **Sample Files**: Download sample news files for testing

## Installation

1. Clone the repository
2. Install dependencies:
   ```
   pip install streamlit joblib pandas PyPDF2 python-docx fpdf requests
   ```
3. Place the trained model files (`fake_news_model.pkl` and `tfidf_vectorizer.pkl`) in the project directory
4. Run the application:
   ```
   streamlit run app.py
   ```

## Usage

1. Select your preferred input method (Local Upload, Google Drive Link, or Paste Text)
2. Provide the news article content
3. Click "Predict" to get the fake news detection result with probability score

## Model

The application uses a machine learning model trained on news datasets to classify articles as real or fake news.
# Fake-vs-Real-news-detection
This project is focused on detecting fake news articles using Natural Language Processing (NLP) and deep learning models. The goal is to help combat the spread of misinformation by building an intelligent system that can classify news text as Fake or Real.
📌 Project Overview
Fake news is intentionally misleading information spread via traditional or social media. Detecting such content is critical for the safety and trust of society. This project leverages machine learning and deep learning techniques to classify news articles based on their content.
🧠 Model Used
The model is trained using TensorFlow/Keras and includes:
Embedding Layer: Converts words into dense vectors.
LSTM/GRU/Dense layers: Learns sequential patterns and context.
Sigmoid Output Layer: Predicts binary class – Fake or Real.
You can also use pre-trained models like:
TF-IDF with Logistic Regression
BERT-based transformer models
📂 Dataset
We used the Fake and Real News Dataset from Kaggle, which contains:
True.csv – Authentic news articles.
Fake.csv – Fabricated or misleading news.
Each file contains:

Title

Text

Subject

Date

🔄 Workflow
Data Cleaning
Remove punctuation, stopwords, lowercase conversion, etc.
Text Tokenization and Vectorization
Using Keras Tokenizer and Padding sequences.
Model Training
Train using binary crossentropy loss and accuracy metrics.
Evaluation
Use accuracy, precision, recall, and F1-score.
Prediction Interface
Interface built using Streamlit or Gradio for easy testing.


# Sentiment Analysis

[View the Jupyter Notebook](./Sentiment_Analysis.ipynb)

## 📊 Dataset
- **Source:** [Twitter API / Amazon Product Reviews / Kaggle]
- **Description:** A text dataset containing user reviews or tweets. Each text entry is labeled with a sentiment class (e.g., Positive, Negative, Neutral).
- **Size:** [Number of rows] rows with text and sentiment labels.

## 🔬 Methodology
1. **Text Preprocessing:** Cleaned text by removing URLs, special characters, and stop words. Applied tokenization, stemming, and lemmatization using NLTK/Spacy.
2. **Text Vectorization:** Converted text into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) and Word Embeddings (Word2Vec / GloVe).
3. **Modeling:** Trained machine learning models (Naive Bayes, SVM) and Deep Learning models (LSTM / BERT) to classify the sentiment.
4. **Evaluation:** Evaluated the models using Accuracy, Precision, Recall, and Confusion Matrix.

## 🏆 Hasil (Results)
- **Best Model:** LSTM (Long Short-Term Memory) Network / SVM.
- **Performance:** Reached 88% precision in correctly identifying positive and negative sentiments.
- **Application:** The model can be used to monitor brand reputation in real-time by automatically classifying incoming user feedback.

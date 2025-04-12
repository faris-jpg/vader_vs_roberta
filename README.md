# vader_vs_roberta

🧠 Sentiment Analysis: VADER vs RoBERTa on Goodreads Reviews

This project compares the performance of two sentiment analysis models — VADER (rule-based) and RoBERTa (transformer-based) — on a set of Goodreads book reviews. The goal is to evaluate their accuracy, efficiency, and misclassification patterns when classifying review sentiments.
📄 Dataset

    Source: Goodreads book reviews (subset from Kaggle)

    Fields used: text (review), rating (1–5 star scale)

🧪 Methods

    VADER: Lexicon and rule-based sentiment analysis

    RoBERTa: Pre-trained transformer model (cardiffnlp/twitter-roberta-base-sentiment)

    Preprocessing included mapping 1–2 stars to negative, 3 to neutral, and 4–5 stars to positive.

📊 Evaluation

    Compared predictions to ground truth from star ratings

    Highlighted key strengths and limitations of each model

⚙️ Tools & Libraries

    Python, Pandas, PyTorch, Hugging Face Transformers

    Seaborn, Matplotlib

    VADER SentimentIntensityAnalyzer

⏱️ Key Insights

    RoBERTa achieved higher accuracy but was significantly slower than VADER.

    VADER frequently misclassified neutral reviews and overestimated positive sentiment.

    A visualization of execution time and model accuracy was included to support the analysis.

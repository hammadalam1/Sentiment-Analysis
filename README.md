# 🧠 Sentiment Analysis with NLTK (CLI Tool)

This is a simple Python command-line tool that performs **sentiment analysis** on user-inputted text using the **NLTK (Natural Language Toolkit)** library. It uses the **VADER (Valence Aware Dictionary and sEntiment Reasoner)** sentiment analysis model.


## 🚀 Features

- Asks the user to input text via the command line.
- Tokenizes the input and removes stopwords.
- Analyzes the sentiment using `SentimentIntensityAnalyzer`.
- Classifies the sentiment as **Positive**, **Negative**, or **Neutral**.
- Displays:
  - Original text
  - Sentiment classification
  - Sentiment scores
  - Filtered words (excluding stopwords)

## 🛠️ Requirements

- Python 3.x
- NLTK library

## 📦 Installation

git clone https://github.com/hammadalam1/Sentiment-Analysis.git
cd Sentiment-Analysis

Install NLTK and download required resources:
pip install nltk

Inside the script, the following will download necessary NLTK datasets:
nltk.download('vader_lexicon')
nltk.download('punkt')
nltk.download('stopwords')

▶️ How to Use
Run the script from your terminal:

 sentiment_analysis.py
Then, enter any sentence when prompted:
Enter a sentence to analyze sentiment: I love this product. It's amazing!

Analysis Result:
Original Text: I love this product. It's amazing!
Sentiment: Positive
Sentiment Scores: {'neg': 0.0, 'neu': 0.413, 'pos': 0.587, 'compound': 0.926}
Filtered Words (no stopwords): ['love', 'product', '.', "'s", 'amazing', '!']

📚 Built With
NLTK
Python Standard Library

📄 License
This project is open-source and available under the MIT License.

✍️ Author
Hammad Alam





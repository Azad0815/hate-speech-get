# hate-speech-det
Hate Speech Detection using Machine Learning

🚀 A simple web app for detecting hate speech in tweets using a Decision Tree Classifier and Streamlit.

Overview

This project analyzes tweets and classifies them into three categories:

Hate Speech
Offensive Language
No Hate and Offensive Content
It uses Natural Language Processing (NLP) techniques for text cleaning and Machine Learning (ML) for classification.

Tech Stack

Python 🐍
Pandas, NumPy for data processing
NLTK for text preprocessing
Scikit-learn for machine learning
Streamlit for the web interface
Installation & Setup

1️⃣ Clone the repository:

git clone https://github.com/your-username/hate-speech-detection.git
cd hate-speech-detection
2️⃣ Install dependencies:

pip install -r requirements.txt
3️⃣ Run the Streamlit app:

streamlit run app.py
How It Works

1️⃣ The dataset is preprocessed (cleaning, tokenization, stemming, stopword removal).
2️⃣ A Decision Tree Classifier is trained on labeled tweet data.
3️⃣ The web app allows users to input a tweet, which is classified in real-time.

Dataset

The dataset used is test_tweets_anuFYb8.csv, which contains:
tweet: The tweet text
id: Labels (0: Hate Speech, 1: Offensive, 2: No Hate/Offensive)
Example Usage

🔹 Run the app, enter a tweet, and get an instant classification result!

Contributing

💡 Feel free to contribute by:

Improving the model
Adding a better dataset
Enhancing UI/UX
License

📜 MIT License – Free to use and modify.


# Twitter-Sentiment-Analysis
NLP-based Twitter sentiment analysis using Logistic Regression

## 📌 Project Overview
This project implements a Twitter Sentiment Analysis system using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to classify tweets as positive or negative based on textual content.

The project demonstrates the complete ML pipeline including data collection, text preprocessing, model training, evaluation, and model serialization.

---

## 📊 Dataset
- Dataset Name: Sentiment140
- Source: Kaggle
- Description: A large dataset of tweets labeled as positive or negative sentiments.

## 🧠 Technologies Used
- Python
- Natural Language Processing (NLP)
- Regular Expressions (Regex)
- Stemming
- Logistic Regression
- Pickle (Model Serialization)

---

## 🔧 NLP Techniques Applied
- Text cleaning using Regex
- Tokenization
- Stopword removal
- Stemming
- Feature extraction (Bag of Words / TF-IDF)

---

## 🤖 Model Used
- Algorithm: Logistic Regression
- Evaluation Metric: Accuracy
- Test Accuracy: ~77.8%
- Model saved using Pickle for future predictions

## 📁 Project Structure
twitter-sentiment-analysis/
├── data/
├── notebooks/
├── src/
├── model/
├── requirements.txt
├── .gitignore
└── README.md

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis

## Install Dependencies
## Make sure Python is installed, then run:

pip install -r requirements.txt

### 3️⃣ Download the Dataset
## This project uses the Sentiment140 dataset from Kaggle.
## Create a Kaggle account
## Generate your Kaggle API key
## Place kaggle.json in your system
## Then run:

kaggle datasets download -d kazanova/sentiment140


## Extract the dataset before use.
## 4️⃣ Run the Notebook
jupyter notebook notebooks/Sentiment_Analysis.ipynb

## 5️⃣ Output
The model will predict whether a tweet has a positive or negative sentiment.

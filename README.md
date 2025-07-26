
# 🧠 Task 3 – Twitter Sentiment Analysis

This project analyzes sentiment-based text data from Twitter. It focuses on cleaning raw tweet data, visualizing word frequency patterns, and calculating sentiment scores for top-mentioned brands.

---

## 🛠️ Tech Stack & Libraries

- **Python 3.x**
- **Jupyter Notebook**
- **pandas**
- **seaborn**
- **matplotlib**
- **nltk**
- **wordcloud**
- **re, string, collections**

---

## 📂 Files Used

- `twitter_training.csv`:  
  Contains 4 columns – `ID`, `Entity`, `Sentiment`, and `Tweet`.

---

## 🧼 Data Cleaning & Preprocessing

- Removed:
  - URLs, hashtags, mentions, and punctuation
  - Extra whitespaces and digits
- Converted text to lowercase
- Removed stopwords using `nltk` and `wordcloud` libraries
- Applied **lemmatization** using `WordNetLemmatizer` to normalize the words

---

## 📊 Visualizations

> **Note:** The notebook contains 11 visualizations in total, including bar charts and word clouds for each sentiment category.  
> Below is a sample preview of just one:

### Net Sentiment Score per Brand
![Net Sentiment Score per Brand](net_sentiment_score.png)

---

## 🔍 Insights

- **Top Words per Sentiment:**  
  Each sentiment class (Positive, Negative, Neutral) shows unique high-frequency terms after refinement and lemmatization.

- **Word Clouds:**  
  Clearly visualized dominant vocabulary for each sentiment — useful for understanding tone and topics.

- **Brand Sentiment Scores:**  
  The top 10 most mentioned brands were analyzed based on sentiment scores, revealing which brands were viewed most positively or negatively.

---

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` notebook and `twitter_training.csv` file.
2. Install the required libraries using pip:

   ```bash
   pip install pandas matplotlib seaborn nltk wordcloud

# 📊 Sentiment Analysis using Python in Google Colab

This project performs a comprehensive sentiment analysis on a text dataset using Python in Google Colab. It demonstrates how a Data Scientist processes, analyzes, and reports insights from raw sentiment-labeled text data. The workflow includes data cleaning, EDA, sentiment prediction using TextBlob, and summary generation.

---

## 📁 Dataset Requirements

Your dataset should be in CSV format with at least the following columns:

| Column Name | Description                              |
|-------------|------------------------------------------|
| `text`      | The raw text data for sentiment analysis |
| `sentiment` | Original sentiment label (`positive`, `negative`, `neutral`) |

### 📌 Example

```csv
text,sentiment
"I love this product!",positive
"This is the worst experience ever.",negative
"Not bad, could be better.",neutral

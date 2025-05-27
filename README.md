# 📊 Social Media Sentiment Analysis using Python in Google Colab

This project demonstrates a complete end-to-end **Sentiment Analysis** pipeline implemented in **Python using Google Colab**. It is designed to showcase how a Data Scientist tackles real-world sentiment-labeled data to extract insights, build predictions, and generate professional reports.

---

## 🧠 Project Objective

To analyze sentiment in textual data, predict the polarity (positive, negative, neutral), and generate a detailed visual and textual summary report.

---

## 🧰 Tools, Libraries, and Technologies Used

| Category          | Tools / Libraries                                           |
|-------------------|-------------------------------------------------------------|
| **Environment**   | Google Colab, Jupyter Notebook                              |
| **Language**      | Python 3                                                    |
| **Data Handling** | Pandas                                                      |
| **Text Cleaning** | NLTK (Natural Language Toolkit), Regular Expressions (re)   |
| **Sentiment Model** | TextBlob                                                  |
| **Visualization** | Seaborn, Matplotlib, WordCloud                              |
| **Evaluation**    | Scikit-learn (Confusion Matrix, Classification Report)      |
| **Report Export** | FPDF (for PDF report generation)                            |
| **Optional**      | CSV file reader (via `upload` in Google Colab)              |

---

## 📁 Dataset Format

Your dataset should be in CSV format with the following required columns:

| Column Name | Description                              |
|-------------|------------------------------------------|
| `text`      | The text input for sentiment analysis    |
| `sentiment` | Labeled sentiment (`positive`, `negative`, `neutral`) |

### 📌 Example CSV

```csv
text,sentiment
"I love this product!",positive
"This is the worst experience ever.",negative
"Not bad, could be better.",neutral

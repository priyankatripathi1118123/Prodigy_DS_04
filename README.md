# Prodigy Infotech – Data Science Internship  
## Task 04: Sentiment Analysis on Twitter Data  

---

## 📌 Objective
The objective of this task is to perform **sentiment analysis on Twitter data** to:
- Clean and preprocess tweet text  
- Analyze sentiment polarity using **TextBlob**  
- Classify tweets as **Positive, Negative, or Neutral**  
- Visualize sentiment distribution overall and across brands  

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data handling and analysis  
- **NumPy** – numerical operations  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical plots  
- **TextBlob** – sentiment analysis  
- **NLTK** – text preprocessing support  

---

## 📊 Dataset Information
- **Dataset Name:** Twitter Training Dataset  
- **File Used:** `twitter_training.csv`  
- **Columns:**
  - `Tweet_ID`
  - `Brand`
  - `Sentiment` (actual label)
  - `Tweet` (raw text)

---

## 🧹 Text Preprocessing
The following preprocessing steps were applied:
- Converted text to lowercase
- Removed URLs, mentions, and hashtags
- Removed special characters and numbers
- Created a cleaned text column for analysis

---

## 🧠 Sentiment Analysis
- Used **TextBlob** to calculate sentiment polarity
- Polarity score ranges from **-1 to +1**
- Tweets were classified as:
  - **Positive** (polarity > 0)
  - **Negative** (polarity < 0)
  - **Neutral** (polarity = 0)

---

## 📈 Visualizations

### 1️⃣ Overall Sentiment Distribution
- Count plot showing number of positive, negative, and neutral tweets

### 2️⃣ Sentiment Distribution Across Brands
- Stacked bar chart displaying sentiment breakdown for each brand

### 3️⃣ Average Sentiment Score per Brand
- Bar chart showing mean polarity score for each brand

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-link>

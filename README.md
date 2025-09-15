# 📈 Stock News Sentiment Analyzer

A lightweight **Streamlit app** that retrieves the latest financial news for a given stock ticker and analyzes the sentiment using a custom **LangChain Tool** powered by **FinBERT** (`ProsusAI/finbert`).

---

## 🔹 Features

- 🔍 Search recent stock market news with **DuckDuckGoSearchResults** (LangChain).  
- 📰 Filter by selected sources (Bloomberg, Reuters, Yahoo Finance, WSJ, etc.).  
- 📊 Perform sentiment analysis (**Positive / Negative / Neutral**) on each news snippet.  
- 💡 Display results in an interactive Streamlit dashboard with:
  - ✅ Highlighted rows (green for positive, red for negative).  
  - 🔗 Clickable links to original articles.  
  - 📈 Confidence scores for sentiment predictions.  
- 🌐 Deployed as a static app using **stlite** (Streamlit in the browser via WebAssembly).  

---

## 🔹 Tech Stack

- **Streamlit** → Interactive UI  
- **LangChain** → News retrieval and tools  
- **DuckDuckGo Search** → Web news results  
- **FinBERT** → Financial sentiment analysis  
- **stlite** → Browser-based deployment (no backend required)  

---

## 📌 Author  

Created by [**Yitsy Mosqueda Cabrera**](https://www.linkedin.com/in/yitsymc/)  

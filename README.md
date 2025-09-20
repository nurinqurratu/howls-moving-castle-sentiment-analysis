# 🎬 Sentiment Analysis of *Howl's Moving Castle* Reviews  

This project performs **sentiment analysis** on user reviews of *Howl’s Moving Castle* collected from **IMDb**.  
The reviews were processed using the **MeaningCloud Sentiment Analysis API** in **RapidMiner** and classified into **positive, negative, or neutral** categories.  

Two machine learning algorithms were applied — **Naive Bayes** and **Decision Tree** — to evaluate classification accuracy and provide insights into the general audience sentiment.  

---

## 🎯 Objectives  
1. Collect **50,000 IMDb reviews** of *Howl’s Moving Castle* and organize them in a structured dataset.  
2. Use **RapidMiner** and the **MeaningCloud API** to automatically classify review sentiment.  
3. Evaluate sentiment classification performance using **Naive Bayes** and **Decision Tree**.  
4. Provide an overview of the audience’s opinions about the movie.  

---

## 🧑‍💻 Project Workflow  
- **Data Collection**: Scraped 50,000 IMDb user reviews of *Howl’s Moving Castle*.  
- **Preprocessing**: Cleaned and structured text data for sentiment analysis.  
- **Sentiment Detection**: Applied **MeaningCloud API** in RapidMiner to categorize reviews (positive, negative, neutral).  
- **Model Training**: Used **Naive Bayes** and **Decision Tree** for sentiment classification.  
- **Evaluation**: Compared algorithm performance based on accuracy.  

---

## 📊 Results  
- **Naive Bayes Accuracy**: **91.3%**  
- **Decision Tree Accuracy**: **89.46%**  

✅ **Naive Bayes outperformed Decision Tree** in sentiment classification for this dataset.  

---

## 🚀 How to Run  
1. Install **RapidMiner Studio**.  
2. Import the project files (`.rmp`).  
3. Connect to the **MeaningCloud API** (API key required).  
4. Load the IMDb reviews dataset.  
5. Run the process to classify sentiments and evaluate results.  

---

## 📂 Dataset  
- **Source**: IMDb reviews of *Howl’s Moving Castle*.  
- **Size**: 50,000 reviews.  
- **Sentiment Labels**: Positive, Negative, Neutral (via MeaningCloud API).  

---

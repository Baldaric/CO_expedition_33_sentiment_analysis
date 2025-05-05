# 🎮 Shadows of Emotion: A Sentiment Analysis of Clair Obscur - Expedition 33

## 🎯 Project Overview
Clair Obscur: Expedition 33 launched on April 24, 2025, receiving immediate attention for its unique visual style and turn-based mechanics. However, aggregated scores alone (e.g., Steam's % rating) lack the nuance needed to understand *why* players liked or disliked the game.  
This project uses NLP and visualization to explore player sentiment, trends, and key discussion points based on user reviews.

---

## 🧩 Problem Statement
- What are players saying beyond the rating?
- Are there recurring themes in praise or criticism?
- How does sentiment evolve post-launch?

---

## 🔍 Project Goals
- Classify Steam review sentiments using **BERT**
- Track changes in sentiment over time (launch to patch)
- Extract popular topics in positive and negative reviews
- Visualize insights to inform both players and developers

---

## 📚 Data Source
- **Platform:** Steam  
- **Tool:** steam API
- **Target:** Clair Obscur: Expedition 33 (App ID: `TBD`)  
- Reviews collected from **April 24** onward

---

## 🛠️ Tools & Libraries
- **Data Collection:** `steamreviews`, `requests`, `pandas`
- **Sentiment Analysis:** `BERT`
- **Visualization:** `matplotlib`, `seaborn`, `wordcloud`

---

## 📈 Key Analysis Steps
1. Data collection with pagination & checkpoint logic
2. Sentiment classification using pretrained BERT model
3. Wordclouds for each sentiment class
4. Playtime vs Sentiment analysis
5. Time-series sentiment trend (launch → patch)
6. Summary insights & recommendations

---

## 📊 Deliverables
- Visual slides for presentation/reporting
- Cleaned CSV dataset of reviews with sentiment labels
- Jupyter Notebook (`.ipynb`) with full pipeline
- GitHub repository with all assets and write-up

---

## ✅ Status
- [ ] App ID confirmed  
- [ ] Reviews collected  
- [ ] BERT sentiment model applied  
- [ ] Visuals generated  
- [ ] LinkedIn post scheduled  

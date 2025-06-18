# 📰 News Aggregation & Topic Modeling with LDA and Clustering

This project uses the [UCI News Aggregator Dataset](https://www.kaggle.com/datasets/uciml/news-aggregator-dataset) to perform:
- Topic modeling using **Latent Dirichlet Allocation (LDA)**
- Visualization of topics using **pyLDAvis**
- Clustering topic distributions with **K-Means**
- Dimensionality reduction with **PCA**
- Word cloud generation for high-frequency terms

---

## 📁 Dataset

**Source**: UCI / Kaggle  
The dataset contains 422,937 news headlines categorized into 4 topics:
- Business (`b`)
- Science/Technology (`t`)
- Entertainment (`e`)
- Health (`m`)

---

## ⚙️ Pipeline Overview

1. Load and preprocess the news headlines
2. Clean and tokenize text
3. Generate bigrams and lemmatize using spaCy
4. Train LDA model and evaluate with Coherence Score
5. Use K-Means to cluster topic distributions
6. Visualize clusters using PCA
7. Create word clouds from lemmatized tokens

---

## 📊 Screenshots

### 🔍 PyLDAvis Topic Visualization
![Screenshot 1](news_Aggregation_us_ml/assets/Screenshot%202025-06-19%20012316.png)

### 📌 K-Means Cluster Plot (PCA)
![Screenshot 2](news_Aggregation_us_ml/assets/Screenshot%202025-06-19%20012341.png)

### ☁️ Word Cloud of News Topics
![Screenshot 3](news_Aggregation_us_ml/assets/Screenshot%202025-06-19%20012350.png)

### 📈 Coherence Score Optimization Plot
![Screenshot 4](news_Aggregation_us_ml/assets/Screenshot%202025-06-19%20012744.png)

---

## 🛠 Dependencies

Install required libraries:

```bash
pip install pandas numpy matplotlib gensim pyLDAvis wordcloud scikit-learn spacy nltk
python -m spacy download en_core_web_sm

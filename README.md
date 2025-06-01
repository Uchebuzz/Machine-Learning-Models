# 🧠 Machine Learning Toolkit: NLP, KMeans, Apriori

Welcome to the **Machine Learning Toolkit** — a modular and practical repository demonstrating key machine learning techniques including **Natural Language Processing (NLP)**, **KMeans clustering**, and the **Apriori algorithm** for association rule mining.

# 🔍 Features

### 🗣️ Natural Language Processing (NLP)
- Text cleaning (lowercasing, stopword removal, lemmatization)
- Sentiment analysis using simple models (e.g., Naive Bayes or pre-trained)
- Vectorization with TF-IDF or CountVectorizer

### 📊 KMeans Clustering
- Unsupervised clustering using `scikit-learn`
- Visualizations with PCA for 2D plotting
- Cluster analysis on text or numerical features

### 🛒 Apriori Algorithm
- Market Basket Analysis using `mlxtend`
- Frequent itemset mining
- Association rule generation with confidence and lift metrics

---

## 🧪 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ml-nlp-kmeans-apriori.git
cd ml-nlp-kmeans-apriori
````

2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Run NLP sentiment analysis:

```bash
python nlp/sentiment_analysis.py
```

### Run KMeans clustering:

```bash
python clustering/kmeans_demo.py
```

### Run Apriori association rules:

```bash
python association_rules/apriori_market_basket.py
```

---

## 🛠️ Dependencies

* `scikit-learn`
* `pandas`
* `nltk`
* `matplotlib`
* `mlxtend` (for Apriori)

Install them all with:

```bash
pip install -r requirements.txt
```

---

## 📈 Sample Outputs

* Word clouds from cleaned text
* Cluster scatter plots
* Association rules table showing support, confidence, and lift

---

## 🧠 Credits

Created by **\[Uche]**
Inspired by real-world business problems like customer segmentation, review analysis, and market basket optimization.

---


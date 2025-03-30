# 🧠 Surveying Bias in Word Embeddings of Political News Media Dataset

This project explores **bias in word embeddings** by analyzing how political ideologies (liberal vs. conservative) affect associations with different social groups. We trained separate models on liberal and conservative news articles and examined biases using metrics such as **WEAT (Word Embedding Association Test)** and **Cohen’s D**.

---

## 📌 Project Overview

Word embeddings are a cornerstone of many NLP applications, but they can reflect and perpetuate **social biases** from their training data. This project:

- Trains word embedding models (**Word2Vec** and **FastText**) on liberal vs. conservative corpora
- Evaluates **gender, race, religion, age, and gender identity** bias
- Uses statistical metrics to quantify bias
- Visualizes results through bar plots and **3D semantic embedding plots**

---

## 📁 Repository Structure


---

## 📊 Dataset

News articles (2016–2020) from:

- **Liberal sources**: CNN, Washington Post, Buzzfeed News
- **Conservative sources**: Fox News, Breitbart, New York Post

These corpora were tokenized, lemmatized, and cleaned for analysis.

---

## 🧪 Tools & Techniques

- **Word Embedding Models**: FastText (Skipgram), Word2Vec (CBOW)
- **Bias Metrics**:
  - WEAT (Word Embedding Association Test)
  - Cohen’s D Effect Size
- **Visualization**: Matplotlib, 3D scatter plots
- **Libraries**: `Gensim`, `FastText`, `WEFE`, `NumPy`, `Matplotlib`

---

## 📈 Key Findings

- **Gender Bias**: Both models associate men with strength/intelligence, and women with weakness/appearance.
- **Religion Bias**: Liberal model showed more bias against Islam in certain contexts.
- **Race Bias**: Liberal model had a slightly more favorable association with Black identity.
- **Age and LGBTQ Bias**: Subtle biases vary between models and categories.
- **Cohen’s D & WEAT** helped quantify and visualize these biases effectively.

---


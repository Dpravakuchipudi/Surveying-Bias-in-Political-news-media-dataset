This project investigates social and political biases in word embeddings trained on liberal and conservative news sources. Using models like Word2Vec and FastText, we explore how biases related to gender, race, religion, age, and gender identity manifest in Natural Language Processing (NLP) representations.

📌 Project Overview
In the era of machine learning, word embeddings have become foundational in NLP tasks. However, these models often reflect and even amplify social biases present in their training data. In this project, we:

Trained separate word embedding models on liberal and conservative news articles
Analyzed bias metrics such as:
WEAT (Word Embedding Association Test)
Cohen’s d effect size
Visualized these biases using bar plots and 3D semantic embedding plots
📂 Repository Structure
├── Group4_Project Report.pdf        # Final report with methodology, results, and discussion
├── Fasttext WEAT Scores.ipynb       # WEAT bias scores calculation using FastText
├── Fasttext Cohen’s D.ipynb         # Cohen’s D calculation and visualizations
├── Word 2 Vec analysis.ipynb        # WEAT evaluation using Word2Vec
├── Screenshot.png                   # Sample visual output (3D embeddings)
├── README.md                        # You're here!
📊 Dataset
We used a preprocessed political news dataset containing articles from:

Liberal Sources: CNN, Washington Post, Buzzfeed News
Conservative Sources: Fox News, Breitbart, New York Post
The dataset includes over 70,000 articles collected from 2016 to 2020, with preprocessing steps such as tokenization and lemmatization applied.

🧪 Techniques & Tools
Word Embedding Models: Word2Vec (Gensim), FastText (Facebook AI)
Bias Metrics: WEAT Score, Cohen’s D
Visualization: Matplotlib, 3D scatter plots
Libraries: Gensim, WEFE (Word Embedding Fairness Evaluation), NumPy, Matplotlib
📈 Key Findings
Gender Bias: Both liberal and conservative models associate males with intelligence/strength more than females.
Religion Bias: Unexpectedly, liberal models showed slightly higher bias against Islam.
Race Bias: Liberal models associated Black individuals more positively than conservative models.
LGBTQ Bias: Liberal models had stronger associations between LGBTQ and weakness in some cases.
▶️ Running the Notebooks
Clone this repository
git clone https://github.com/yourusername/word-embedding-bias-nlp.git
cd word-embedding-bias-nlp
Install dependencies
pip install -r requirements.txt
Run Jupyter Notebook
jupyter notebook
⚠️ Note: Some embeddings (e.g., BERT/GloVe) were excluded due to training constraints.

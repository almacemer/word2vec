This project trains a custom Word2Vec model using the Gensim library on a dataset of news articles. The goal is to generate word embeddings that capture semantic relationships between words — for example, "king" - "man" + "woman" ≈ "queen".

## About the Project
- Used a collection of news articles and books for training
- Preprocessed text by:
  - Lowercasing
  - Removing punctuation and stopwords
  - Tokenizing sentences
- Trained a Word2Vec model using the skip-gram approach
- Explored most similar words and vector arithmetic

## Technologies Used
- Python
- Gensim
- NLTK
- Matplotlib (for simple visualizations)

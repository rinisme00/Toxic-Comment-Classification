# Toxic-Comment-Classification

# CyberSoft Final Project

# How to run the streamlit notebook
1. Open the notebook on Kaggle https://www.kaggle.com/code/rin0823/streamlit-app
2. In Kaggle input panel, add the trained models https://www.kaggle.com/models/rin0823/toxic-comment-classification-models/
3. In **Add-ons** tab, select **Secrets** and add:
   - Label: NGROK_AUTH_TOKEN
   - Value: "Add your ngrok auth token here"
4. Run the notebook's cells from top to bottom
5. Open the public Ngrok URL for Streamlit demo

# Details
## 1. Binary Classification
- Models:
  + Machine Learning: SVM, Logistic Regression, Naive-Bayes with TF-IDF Embeddings
  + Deep Learning: GRU with Word2Vec Embeddings

## 2. Multi-label Classification
- Models:
  + Machine Learning: SVM, Logistic Regression, Naive-Bayes with TF-IDF Embeddings
  + Deep Learning: Bidirectional LSTM with Word2Vec Embeddings, Bidirectional GRU and RoBERTa

# Datasets and Kaggle work
- Machine Learning: https://www.kaggle.com/code/rin0823/toxic-comment-classifier-machine-learning
- BiLSTM and GRU: https://www.kaggle.com/code/rin0823/toxic-comment-classifier-deep-learning
- BiGRU and RoBERTa: https://www.kaggle.com/code/rin0823/toxic-comment-classifier-bigru-and-roberta
- Jigsaw Toxic Comment Classification Challenge: https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data

# Demo video:
https://drive.google.com/drive/folders/1aE4sbF5X7cuKA-XFkCyYlxHSdLszznGJ?usp=sharing

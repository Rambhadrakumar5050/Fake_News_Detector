# Fake News Detection using Transformers

## 📌 Project Overview
Binary classification model to detect fake vs real news articles using BERT and traditional machine learning.

## 📊 Dataset
- **Source:** Kaggle Fake News Detection dataset
- **Real news:** 21,417 samples
- **Fake news:** 23,481 samples
- **Total:** 44,898 samples
- **Labels:** 0 = Real news, 1 = Fake news

## 🚀 Quick Installation

### 1. Clone & Setup
```bash
git clone https://github.com/rambhadrakumar5050/fake-news-detection.git
cd fake-news-detection
pip install pandas numpy scikit-learn transformers torch datasets matplotlib seaborn evaluate nltk tqdm jupyter

##Run the Jupyter Notebook
jupyter notebook notebooks/fake-news.ipynb

##results
📊 Results
Model	        Accuracy	       F1-Score	    Precision	  Recall
TF-IDF+          	95.6%	        95.8%	       96.2%	   95.4%
BERT Fine-tuned	To be evaluated	 To be evaluated	To be evaluated	 To be evaluated

###Project structure

fake-news-detection/
├── notebooks/           # Jupyter notebooks
├── requirements.txt     # Dependencies
├── README.md           # This file
├── .gitignore          # Files to ignore
└── data/              # Dataset information


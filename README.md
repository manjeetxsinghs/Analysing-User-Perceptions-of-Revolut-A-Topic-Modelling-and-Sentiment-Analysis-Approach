# **Analysing User Perceptions of Revolut: A Topic Modelling and Sentiment Analysis Approach**

## **Overview**

This project applies Natural Language Processing (NLP) techniques to analyse user-generated content regarding Revolut, a major fintech platform. By combining web scraping, lexicon-based sentiment analysis, and advanced transformer-based topic modelling, the study uncovers key drivers of positive and negative customer sentiment.

## **Key Features**

* **Web Scraping Pipeline:** Custom scrapers using Requests and BeautifulSoup to collect 3,126 documents across Reddit (4 subreddits via JSON endpoints) and Trustpilot.  
* **Rigorous Data Preprocessing:** Text normalisation, NLTK tokenisation, custom stopword removal, and lemmatisation achieving 72.4% data retention ($n=2,264$).  
* **Sentiment Analysis:** Implements VADER (Valence Aware Dictionary and sEntiment Reasoner) to classify review polarities (Positive: 59.5%, Negative: 28.4%, Neutral: 12.1%).  
* **Topic Modelling:** Employs BERTopic with Sentence-BERT embeddings, UMAP, and HDBSCAN clustering to extract 20 distinct topics and 8 primary thematic clusters


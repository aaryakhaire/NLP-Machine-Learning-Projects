# NLP & Machine Learning Projects

A collection of practical Natural Language Processing (NLP) and Machine Learning projects covering text preprocessing, sentiment analysis, named entity recognition, topic modelling, text classification, clustering, and information retrieval.

The projects demonstrate the application of NLP and machine learning techniques to structured and unstructured text data, including preprocessing, feature engineering, model development, evaluation, visualization, and similarity-based retrieval.

---

## Projects

### 01. Text Preprocessing and Sentiment Classification

A text analytics pipeline covering text preprocessing, linguistic normalization, feature representation, named entity recognition, and sentiment classification.

**Key Techniques:**
- Tokenization
- Stop-word removal
- Stemming
- Lemmatization
- Named Entity Recognition
- N-gram analysis
- Bag of Words
- TF-IDF
- Naive Bayes classification
- Sentiment evaluation

---

### 02. Named Entity Recognition and Topic Modelling

An NLP pipeline that extracts named entities from news articles and identifies underlying topics using unsupervised topic modelling.

**Key Techniques:**
- Named Entity Recognition using spaCy
- PERSON, ORG, GPE, and DATE entity extraction
- Text preprocessing
- Tokenization
- Stop-word removal
- Lemmatization
- Gensim Dictionary and Corpus
- Latent Dirichlet Allocation (LDA)
- Topic distribution analysis
- Entity-topic relationships
- Topic visualization
- Word clouds

---

### 03. News Article Classification

A supervised machine learning project for categorizing news articles into predefined categories using traditional NLP feature representations and classification algorithms.

**Key Techniques:**
- Text preprocessing
- Tokenization
- Stop-word removal
- Lemmatization
- Bag of Words
- TF-IDF
- Train-test splitting
- Multinomial Naive Bayes
- Logistic Regression
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Misclassification analysis

---

### 04. Customer Feedback Clustering

An unsupervised learning project that identifies recurring themes and patterns in customer feedback using text vectorization and clustering.

**Key Techniques:**
- Text preprocessing
- Tokenization
- Stop-word removal
- Lemmatization
- TF-IDF feature extraction
- K-Means clustering
- Elbow method
- Cluster analysis
- Representative feedback analysis
- Word cloud visualization
- Theme identification
- Service improvement recommendations

---

### 05. Mini Search Engine

A lightweight information retrieval system that processes user queries and ranks relevant news articles based on textual similarity.

**Key Techniques:**
- Text preprocessing
- Tokenization
- Stop-word removal
- Lemmatization
- Bag of Words
- TF-IDF
- Query processing
- Cosine similarity
- Document ranking
- Top-k retrieval
- Similarity score visualization

The project uses the UCI News Aggregator Dataset containing real-world news headlines and associated metadata.

---

## Technologies and Libraries

### Programming Language

- Python

### Natural Language Processing

- NLTK
- spaCy

### Machine Learning

- Scikit-learn
- Gensim

### Data Processing

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- WordCloud
- pyLDAvis

### Development Environment

- Google Colab
- Jupyter Notebook

---

## Project Structure

```text
NLP-Machine-Learning-Projects/
│
├── 01_Text_Preprocessing_Sentiment_Classification.py
├── 02_NER_and_Topic_Modelling.py
├── 03_News_Article_Text_Classification.py
├── 04_Customer_Feedback_Clustering.py
├── 05_Mini_Search_Engine.py
│
├── README.md
└── requirements.txt

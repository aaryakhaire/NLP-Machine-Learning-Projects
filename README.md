
# NLP & Machine Learning Projects

A collection of practical Natural Language Processing (NLP) and Machine Learning projects covering the complete text analytics workflow, from text preprocessing and feature representation to classification, clustering, topic modelling, and information retrieval.

The projects demonstrate the application of classical machine learning and NLP techniques on both structured and unstructured textual data.

---

## Projects

### 01. Text Preprocessing and Sentiment Classification

Explores fundamental NLP preprocessing and text representation techniques for sentiment analysis.

**Key techniques:**
- Text tokenization
- Stop-word removal
- Stemming and lemmatization
- Named Entity Recognition
- N-gram generation
- Bag of Words
- TF-IDF
- Naive Bayes classification
- Sentiment classification evaluation

---

### 02. Named Entity Recognition and Topic Modelling

Identifies important entities in news articles and discovers underlying topics using unsupervised learning.

**Key techniques:**
- Named Entity Recognition using spaCy
- Entity extraction for PERSON, ORG, GPE, and DATE
- Text preprocessing
- Lemmatization
- Gensim Dictionary and Corpus
- Latent Dirichlet Allocation (LDA)
- Topic distribution analysis
- Entity-topic relationships
- Topic visualization and word clouds

---

### 03. News Article Text Classification

Builds supervised machine learning models for categorizing news articles into predefined categories.

**Key techniques:**
- Text preprocessing
- Tokenization and lemmatization
- Bag of Words
- TF-IDF
- Train-test splitting
- Multinomial Naive Bayes
- Logistic Regression
- Accuracy, Precision, Recall, and F1-score
- Confusion matrix analysis
- Misclassification analysis

---

### 04. Customer Feedback Clustering

Uses unsupervised machine learning to identify common themes and patterns in customer feedback.

**Key techniques:**
- Text preprocessing
- Tokenization and lemmatization
- TF-IDF feature extraction
- K-Means clustering
- Elbow method for cluster selection
- Cluster analysis
- Representative feedback analysis
- Word cloud visualization
- Customer service improvement recommendations

---

### 05. Mini Search Engine

Implements a lightweight search engine capable of retrieving and ranking news articles based on query relevance.

**Key techniques:**
- Text preprocessing
- Lemmatization
- Bag of Words
- TF-IDF
- Cosine similarity
- Query processing
- Document ranking
- Top-k search results
- Similarity score visualization

The project uses the UCI News Aggregator dataset containing real-world news headlines and metadata.

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

### Data Processing and Visualization

- Pandas
- NumPy
- Matplotlib
- WordCloud

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
└── README.md
````

---

## Skills Demonstrated

This repository demonstrates practical experience with:

* Natural Language Processing
* Text preprocessing and normalization
* Feature engineering for textual data
* Bag-of-Words representation
* TF-IDF representation
* N-gram analysis
* Named Entity Recognition
* Topic Modelling
* Supervised Text Classification
* Unsupervised Text Clustering
* Information Retrieval
* Similarity and Ranking Algorithms
* Model Evaluation
* Data Visualization
* Exploratory Text Analysis

---

## Datasets

The projects use a combination of structured, synthetic, and real-world textual datasets depending on the requirements of each experiment.

The Mini Search Engine project uses the **UCI News Aggregator Dataset**, which contains news articles and associated metadata across multiple categories.

Dataset source:

[UCI Machine Learning Repository - News Aggregator Dataset](https://archive.ics.uci.edu/dataset/359/news+aggregator)

The complete dataset is not included in this repository due to its size. Instructions for obtaining the dataset are provided in the relevant project.

---

## How to Run

The projects are designed to run in Google Colab or a local Python environment.

### 1. Clone the repository

```bash
git clone https://github.com/aaryakhaire/NLP-Machine-Learning-Projects.git
cd NLP-Machine-Learning-Projects
```

### 2. Install the required libraries

```bash
pip install pandas numpy nltk spacy scikit-learn gensim matplotlib wordcloud
```

### 3. Run the desired project

Each Python file contains the complete implementation for its respective experiment.

For projects requiring external datasets, download the required dataset and place it in the appropriate working directory before execution.

---

## Project Progression

The projects follow a progression from foundational NLP techniques to more advanced text analytics applications:

```text
Text Preprocessing
        |
        v
Feature Representation
        |
        v
Text Classification
        |
        v
Topic Modelling & Entity Analysis
        |
        v
Text Clustering
        |
        v
Information Retrieval & Search
```

This progression demonstrates how textual data can be transformed from raw language into structured representations and subsequently used for analysis, prediction, clustering, and retrieval.

---

## Repository Purpose

This repository serves as a practical portfolio of NLP and Machine Learning implementations, demonstrating the application of different techniques to real-world text analytics problems.

The projects emphasize understanding the complete workflow rather than relying solely on pre-built models, including data preprocessing, feature engineering, model development, evaluation, visualization, and interpretation of results.

---

## Author

**Aarya Khaire**

GitHub: [github.com/aaryakhaire](https://github.com/aaryakhaire)


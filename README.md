# NLP

# NLP Assignments Repository

This repository contains a collection of Natural Language Processing (NLP) assignments implemented as part of coursework. The assignments cover foundational and applied NLP concepts such as tokenization, stemming, lemmatization, vectorization, embeddings, named entity recognition, semantic analysis, machine translation, sentiment analysis, word sense disambiguation, and N-gram-based autocomplete.

## Repository Objective

The objective of this repository is to provide hands-on implementation of important NLP techniques using Python and popular libraries such as NLTK, scikit-learn, and Word2Vec. Each assignment focuses on a core NLP task and helps in understanding how text data can be cleaned, represented, analyzed, and used in real-world language applications.

## Assignments Overview

### 1. Tokenization, Stemming, and Lemmatization
This assignment focuses on the basic preprocessing steps in NLP.

Tasks included:
- Perform **tokenization** using NLTK methods:
  - Whitespace Tokenization
  - Punctuation-based Tokenization
  - Treebank Tokenization
  - Tweet Tokenization
  - MWE (Multi-Word Expression) Tokenization
- Apply **Porter Stemmer**
- Apply **Snowball Stemmer**
- Perform **Lemmatization** using any suitable technique

**Learning outcome:** Understand how raw text is broken into tokens and normalized using stemming and lemmatization techniques.

---

### 2. Bag-of-Words, TF-IDF, and Word2Vec Embeddings
This assignment focuses on converting text into numerical representations for machine learning.

Tasks included:
- Apply **Bag-of-Words**
  - Count occurrence
  - Normalized count occurrence
- Apply **TF-IDF**
- Create **Word2Vec embeddings**

**Learning outcome:** Learn different text representation techniques ranging from simple frequency-based methods to dense semantic embeddings.

---

### 3. Text Cleaning, Stop Word Removal, Lemmatization, Label Encoding, and TF-IDF
This assignment involves building a complete preprocessing pipeline for textual datasets.

Tasks included:
- Perform **text cleaning**
- Apply **lemmatization**
- Remove **stop words**
- Apply **label encoding**
- Create **TF-IDF representations**
- Save the processed outputs

**Learning outcome:** Understand end-to-end preprocessing required before training NLP models.

---

### 4. Named Entity Recognition (NER) System
This assignment focuses on extracting useful entities from real-world text such as news articles or social media posts.

Tasks included:
- Build a **Named Entity Recognition (NER)** system
- Extract entities such as:
  - Person names
  - Locations
  - Organizations
  - Dates and other named entities
- Measure performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

**Learning outcome:** Learn how information extraction works and how to evaluate NLP classification systems.

---

### 5. Semantic Relationships Using WordNet
This assignment explores lexical semantics using the WordNet database.

Tasks included:
- Identify **synonymy**
- Identify **antonymy**
- Identify **hypernymy**

**Learning outcome:** Understand semantic relationships between words and how lexical databases support language understanding.

---

### 6. Machine Translation System
This assignment focuses on developing a system for translating public information content between English and any Indian language.

Tasks included:
- Build a **Machine Translation** system
- Translate text between:
  - English and Hindi
  - English and Marathi
  - English and any other Indian language

**Learning outcome:** Explore multilingual NLP and the challenges of language translation for Indian languages.

---

### 7. Text Preprocessing and Analysis Application Using NLTK
This assignment involves developing an NLP application that performs basic text analysis tasks.

Tasks included:
- Tokenization
- POS Tagging
- Basic NLP operations using NLTK

**Learning outcome:** Gain practical understanding of text analysis workflows using the NLTK library.

---

### 8. Word Sense Disambiguation Using WordNet
This assignment focuses on resolving ambiguity in sentences where a word may have multiple meanings.

Tasks included:
- Apply **Word Sense Disambiguation (WSD)**
- Use **WordNet-based methods**
- Improve meaning interpretation in ambiguous sentences

**Learning outcome:** Learn how context helps in identifying the correct meaning of a word.

---

### 9. Sentiment Analysis for Indian Language
This assignment focuses on classifying text sentiment in an Indian language using an appropriate NLP or machine learning algorithm.

Tasks included:
- Select an appropriate algorithm
- Perform **sentiment analysis**
- Classify text into sentiments such as:
  - Positive
  - Negative
  - Neutral

**Learning outcome:** Understand sentiment classification in multilingual or regional language settings.

---

### 10. Auto-complete Algorithm Using N-gram Model
This assignment involves building an autocomplete system using an N-gram language model.

Tasks included:
- Build an **N-gram model**
- Predict the next word or phrase based on previous words
- Apply the model to auto-complete text input

Applications mentioned:
- Translation
- Author identification
- Speech recognition

**Learning outcome:** Learn how probabilistic language models are used for prediction and text generation tasks.

---

## Suggested Repository Structure

```text
nlp-assignments/
│
├── Assignment-1-Tokenization-Stemming-Lemmatization/
├── Assignment-2-BOW-TFIDF-Word2Vec/
├── Assignment-3-Text-Cleaning-TFIDF/
├── Assignment-4-NER-System/
├── Assignment-5-WordNet-Semantic-Relations/
├── Assignment-6-Machine-Translation/
├── Assignment-7-NLTK-Text-Analysis/
├── Assignment-8-Word-Sense-Disambiguation/
├── Assignment-9-Sentiment-Analysis-Indian-Language/
├── Assignment-10-Ngram-Autocomplete/
│
├── datasets/
├── outputs/
├── requirements.txt
└── README.md

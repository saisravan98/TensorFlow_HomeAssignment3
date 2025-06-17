# Home Assignment 3 - NLP & Deep Learning Tasks

*Student Name:* SAI SRAVAN CHINTALA  
*Student ID:* 700773836

## 📚 Overview

This project consists of five NLP and deep learning tasks, implemented using Python, TensorFlow, NLTK, spaCy, and HuggingFace Transformers. Each task explores different concepts in modern NLP pipelines, from sequence generation using LSTMs to sentiment analysis with pre-trained transformers.

---

## 🧠 Task Breakdown

### 🔤 Q1: RNN for Character-Level Text Generation

•⁠  ⁠*Goal*: Build an LSTM-based RNN to generate text character-by-character from Shakespeare’s dataset.
•⁠  ⁠*Key Steps*:
  - Load and preprocess the text.
  - Tokenize characters and create sequences.
  - Train an LSTM model using TensorFlow.
  - Generate new text using a sampling function with temperature control.
•⁠  ⁠*Key Concept*:  
  Temperature scaling adjusts randomness during text generation:
  - High temp → creative, less predictable
  - Low temp → deterministic, repetitive

---

### 🧼 Q2: Basic NLP Preprocessing

•⁠  ⁠*Goal*: Tokenize a sentence, remove stopwords, and apply stemming.
•⁠  ⁠*Libraries*: NLTK
•⁠  ⁠*Example Sentence*:  
  ⁠ "NLP techniques are used in virtual assistants like Alexa and Siri." ⁠
•⁠  ⁠*Steps*:
  1. Tokenization  
  2. Stop word removal  
  3. Stemming using ⁠ PorterStemmer ⁠

---

### 🏷️ Q3: Named Entity Recognition (NER)

•⁠  ⁠*Goal*: Identify named entities from a sentence using spaCy.
•⁠  ⁠*Example Input*:  
  ⁠ "Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009." ⁠
•⁠  ⁠*Output*: List of detected entities with their type and character positions.

---

### 🧮 Q4: Scaled Dot-Product Attention

•⁠  ⁠*Goal*: Implement the core attention mechanism behind Transformers.
•⁠  ⁠*Steps*:
  1. Compute dot product of Q and Kᵀ
  2. Scale by √d
  3. Apply softmax to get attention weights
  4. Multiply weights with V
•⁠  ⁠*Test Input*: Small example matrices for Q, K, V
•⁠  ⁠*Output*: Attention weights and final attention output

---

### 😀 Q5: Sentiment Analysis with HuggingFace

•⁠  ⁠*Goal*: Use a pre-trained transformer to analyze sentiment of a sentence.
•⁠  ⁠*Library*: HuggingFace Transformers (⁠ pipeline ⁠)
•⁠  ⁠*Input Sentence*:  
  ⁠ "Despite the high price, the performance of the new MacBook is outstanding." ⁠
•⁠  ⁠*Output*: Sentiment label and confidence score

---

## 📌 Short Answer Questions

Each section includes well-explained short answers for concepts such as:
•⁠  ⁠*Stemming vs Lemmatization*
•⁠  ⁠*NER vs POS tagging*
•⁠  ⁠*Self-attention mechanism*
•⁠  ⁠*Benefits of Pre-trained Models (BERT vs GPT)*

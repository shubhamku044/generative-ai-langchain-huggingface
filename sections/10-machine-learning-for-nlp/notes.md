# Section 10 Notes — Machine Learning For NLP

> Rule: after each lecture, write the gist here **in my own words** before moving on.

## 1. NLTK Fundamentals

### 01. Roadmap To Learn NLP
- 

### 02. Practical Usecases Of NLP
- 

### 03. Tokenization and Basic Terminologies
- Corpus / Document / Vocabulary / Tokens — definitions in my own words:
- 

### 04. Tokenization Practicals
- Sentence vs word tokenization: which NLTK API, when to use which
- 

### 05. Stemming Using NLTK
- Why stem? PorterStemmer quirks (e.g. "history"→"histori")
- 

### 06. Lemmatization
- Stemming vs lemmatization — speed vs correctness tradeoff, WordNetLemmatizer + POS matters
- 

### 07. Stopwords
- When removing stopwords helps / hurts (sentiment vs negation!)
- 

### 08. POS Tagging
- 

### 09. Named Entity Recognition
- 

## 2. Text Vectorization

### 11. One Hot Encoding
- Idea, and why it breaks at scale:
- 

### 13. Bag Of Words
- Formula/idea, vocabulary size, sparse matrix:
- 

### 16. N-Grams
- Unigram/bigram/trigram — what context they capture:
- 

### 18. TF-IDF
- $TF = \frac{\text{count of } t \text{ in } d}{\text{total terms in } d}$, $IDF = \log\frac{N}{\text{df}(t)}$
- Why multiplying by IDF helps:
- 

## 3. Word Embeddings

### 21. Word Embeddings
- Dense vs sparse vectors; distributional hypothesis:
- 

### 22–24. Word2Vec: CBOW vs Skip-Gram
- CBOW: context → target. Skip-gram: target → context.
- Window size, training intuition:
- 

### 26. Average Word2Vec
- Why averaging word vectors gives a document vector:
- 

## Open questions / things to revisit

- 

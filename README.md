## 🧠 Natural Language Processing (NLP) Labs

**Author:** Abdulrahman Alamodi  
**Institution:** Albukhary International University (AIU)  

This repository contains a comprehensive collection of practical lab assignments and projects for my **Natural Language Processing** coursework. It documents the journey from fundamental text processing to advanced machine learning and deep learning applications in NLP.

---

## 📘 Repository Overview

Natural Language Processing bridges the gap between human communication and computer understanding. This repository serves as a practical portfolio, demonstrating how to transform unstructured, raw text into structured data, extract meaningful features, and build predictive or generative models. 

Each notebook represents a specific milestone in the NLP pipeline, heavily utilizing industry-standard libraries like **Python**, **NLTK**, and **spaCy**.

---

## 📂 Repository Architecture

```text
NLP-Labs/
├── 📓 Building NLP Pipelines.ipynb
├── 📓 Understanding & Analyzing Words, Phrases an...ipynb
├── 📓 Feature Engineering.ipynb
├── 📓 Text_Classification.ipynb
├── 📓 Text_Clustering.ipynb
├── 📓 Topic_Modeling.ipynb
├── 📓 Text_Summarization.ipynb
├── 📓 Text_to_Speech_(TTS)_and_Translation.ipynb
└── 📄 README.md

```

---

## 🧩 Detailed Lab Breakdown

### 🛠️ Lab 1: Building NLP Pipelines

* **File:** `Building NLP Pipelines.ipynb`
* **Focus:** Text Preprocessing and Standardization
* **Techniques Implemented:** Tokenization (sentence and word level), stemming, lemmatization, stop word removal, Part-of-Speech (POS) tagging, dependency parsing, and Named Entity Recognition (NER).

### 🔍 Lab 2: Syntactic Analysis

* **File:** `Understanding & Analyzing Words, Phrases an...ipynb`
* **Focus:** Understanding Words, Phrases, and Clauses
* **Techniques Implemented:** Explored deep syntactic structures by performing phrase chunking utilizing NLTK, clause identification with spaCy, and generating hierarchical syntax trees to understand sentence grammar.

### 🔢 Lab 3: Feature Engineering

* **File:** `Feature Engineering.ipynb`
* **Focus:** Converting Text into Numerical Representations
* **Techniques Implemented:** Transitioned from text to math using One-Hot Encoding, N-grams, and TF-IDF. Trained custom continuous word embeddings (CBOW & Skip-gram models) and evaluated their multidimensional relationships using T-SNE visualizations.

### 📊 Lab 4: Text Classification

* **File:** `Text_Classification.ipynb`
* **Focus:** Supervised Machine Learning for Categorization
* **Techniques Implemented:** Applied the full NLP pipeline to real-world tasks (spam detection and news categorization). Utilized Bag-of-Words and TF-IDF vectorization to train and evaluate multiple classification models, including Naive Bayes, Support Vector Machines (SVM), Logistic Regression, and Random Forest.

### 🧩 Lab 5: Text Clustering

* **File:** `Text_Clustering.ipynb`
* **Focus:** Unsupervised Machine Learning for Document Grouping
* **Techniques Implemented:** Applied unsupervised algorithms (like K-Means) to group similar documents together, discover latent structures within unlabelled text data, and analyze cluster characteristics.

### 📌 Lab 6: Topic Modeling

* **File:** `Topic_Modeling.ipynb`
* **Focus:** Discovering Overarching Themes in Corpora
* **Techniques Implemented:** Implemented advanced statistical modeling to scan large collections of documents, automatically identifying and extracting the underlying abstract "topics" or themes spread across the text.

### 📝 Lab 7: Text Summarization

* **File:** `Text_Summarization.ipynb`
* **Focus:** Extractive & Abstractive Summarization Methods
* **Techniques Implemented:** Explored both approaches to summarization. Implemented graph-based algorithms (TextRank and LexRank) for extractive summarization. Built an Encoder–Decoder Seq2Seq model for abstractive generation, evaluating the quality of outputs using ROUGE metrics.

### 🗣️ Lab 8: Audio & Cross-Lingual Processing

* **File:** `Text_to_Speech_(TTS)_and_Translation.ipynb`
* **Focus:** Text-to-Speech (TTS) and Machine Translation
* **Techniques Implemented:** Extended text processing into audio generation by converting text sequences into synthesized speech, alongside implementing cross-lingual translation tasks to bridge language barriers.

---

## 🧮 Technologies & Frameworks

This repository relies on a robust stack of data science and machine learning tools:

**Core Languages & Environments:**

* Python 3.x
* Jupyter Notebook / Google Colab

**NLP & Text Processing:**

* `NLTK` (Natural Language Toolkit)
* `spaCy`
* `Gensim` (for Topic Modeling and Embeddings)

**Machine Learning & Deep Learning:**

* `Scikit-Learn` (for classification, clustering, and evaluation metrics)
* Deep Learning frameworks (TensorFlow / Keras / PyTorch) used for custom embeddings and Seq2Seq summarization.

---

## 🚀 How to Use This Repository

1. **Clone the repository:**
```bash
git clone [https://github.com/Alamodi123/NLP-Labs.git](https://github.com/Alamodi123/NLP-Labs.git)
cd NLP-Labs

```


2. **Install dependencies:**
Ensure you have the required NLP libraries installed:
```bash
pip install nltk spacy scikit-learn jupyter
python -m spacy download en_core_web_sm

```


3. **Launch Jupyter Notebook:**
```bash
jupyter notebook

```


Navigate to the desired `.ipynb` file to run the cells and explore the code.

```

```

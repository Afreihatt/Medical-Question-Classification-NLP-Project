# Medical-Question-Classification-NLP-Project

**Goal:** Automating the classification of Arabic medical questions to route them to the correct medical specialty, improving patient care efficiency and response time.

**Classify patient medical questions automatically so that they are directed to the right medical experts.**

Medical NLP is challenging due to:

- Specialized medical terminology.

- Context-dependent meanings.

- Multilingual data (Arabic/English).

The critical need for high accuracy, where misclassification could harm patient care.

The main objective of this project is **to compare traditional machine learning techniques with modern deep learning models** to determine which method provides:

- The highest accuracy.

- Fastest inference time.

- Practical feasibility for real-world healthcare systems.

Dataset

Total Arabic Questions: 26,863

Domain: Medical

Task Type: Multi-class Classification

Questions span multiple medical specialties, making the task complex and realistic.

Tools & Technologies
Category     /	   Libraries
Programming Language	Python 🐍
Preprocessing	NLTK, langdetect
Embeddings	TF-IDF , Word2Vec, FastText, BERT
Traditional ML Models	SVM, Logistic Regression, Naive Bayes
Deep Learning Models	LSTM, GRU, SimpleRNN
Transformer Models	AraBERT, AraGPT2
Visualization & Analysis	Matplotlib, Seaborn

**Insights**

Fine-tuned Transformers are best for accuracy but require more computational power.

Aggressive preprocessing improves traditional ML performance but harms transformer models.

There’s a speed vs. accuracy trade-off:

TF-IDF + SVM = faster, lightweight, slightly lower accuracy.

BERT = slower, resource-heavy, but highest accuracy.

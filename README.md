## Overview
This project was presented as my Thesis in my Bachelor's degree. It implements a semantic hate speech detection system based on vector embeddings and information retrieval.

A vector database is built using **FAISS** to efficiently index and retrieve semantic representations of text generated with **Sentence Transformers**. Two different classification strategies are implemented and compared:

- **k-Nearest Neighbors (k-NN)**
- **Large Language Model (Gemini) using Retrieval-Augmented Generation (RAG)**

---

## Features

- Semantic text representation using Sentence Transformers
- Vector database indexing with FAISS
- Flat Index nearest-neighbor retrieval
- Hate speech classification using k-NN
- Hate speech classification using Gemini + RAG
- Performance evaluation using standard classification metrics

---


## Technologies

- Python
- Google Colab
- Sentence Transformers
- FAISS
- scikit-learn
- Pandas
- NumPy
- KaggleHub
- Google AI Studio (Gemini API)

---

## Datasets

The project combines public hate speech datasets from:

- Hate Speech Detection Curated Dataset (Kaggle)
- hatespeech_18 (Hugging Face)
- Hate Speech Classification Dataset (Kaggle) (evaluation dataset)
- 
The datasets are integrated into a unified knowledge base used to generate semantic embeddings.

---

If you use this project for research or educational purposes, please consider citing this repository.

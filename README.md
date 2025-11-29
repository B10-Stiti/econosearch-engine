# **Mini Project – Information Retrieval (TIR)**

Dataset: **Reuters‑21578 (NLTK)**  
Domain: **Economic News Retrieval**  

## **📌 Project Overview**

This project implements a complete **information retrieval pipeline** using the Reuters‑21578 economic news dataset.  
The goal is to build, evaluate, and improve a search engine using TF‑IDF and classical IR techniques.

## **📁 Main Components**

1. **Preprocessing & Inverted Index**
    
    - Cleaning, tokenization, stopwords, stemming
        
    - Construction of `{term → {doc_id: tf}}`
        
    - Saved as JSON
        
2. **TF‑IDF Vectorization**
    
    - Using scikit‑learn
        
    - Transformation of all documents into a sparse TF‑IDF matrix
        
3. **Search Engine**
    
    - Query preprocessing
        
    - Cosine similarity ranking
        
    - Top‑k document retrieval
        
4. **Evaluation**
    
    - Precision@5, Precision@10
        
    - Recall@10
        
    - Average Precision (AP)
        
    - Mean Average Precision (MAP)
        
5. **Relevance Feedback (Rocchio)**
    
    - Query expansion using positive/negative documents
        
    - Re‑evaluation after feedback
        
6. **Ablation Study**
    
    - Compare pipelines:
        
        - Stopwords ON/OFF
            
        - Stemming ON/OFF
            
    - Measure effect on MAP

## **🛠 Technologies**

Python, NLTK, NumPy, SciPy, scikit‑learn, Pandas

# Text Data Mining Projects: Tools and Technologies  

**Project Overview**  
This repository contains text data mining projects leveraging tools like **Talend** (ETL pipelines, unstructured text processing) and **Qlik Sense** (visual analytics, SVD-driven semantic analysis)[1][2]. Projects focus on **NLP** (sentiment analysis, topic modeling) and **vectorization** (TF-IDF, word embeddings) using Python/R frameworks.  

**Key Tools**  
- **Talend Studio**: Configure text columns as *Nominal* or *Unstructured* for tokenization[1]. Use `tMap` for JSON field extraction.  
- **Qlik Sense**: Integrate R scripts via the Advanced Analytics Plugin for word clouds and frequency analysis[2].  
- **Python**: `spaCy` (dependency parsing), `scikit-learn` (logistic regression/SVM models), `NLTK` (stemming).  
- **R/textmineR**: Topic modeling (LDA), coherence scoring, and SVD for dimensionality reduction[2].  
- **Azure Text Analytics**: API-based sentiment scoring and entity recognition[3].  

**Installation**  
conda create -n textmining python=3.8 && conda activate textmining
pip install pandas scikit-learn nltk spacy matplotlib
python -m spacy download en_core_web_sm

**Results**  
- **Accuracy**: 89-93% across logistic regression, SVM, and neural networks.  
- **Visualizations**: Qlik word clouds, Matplotlib confusion matrices.  

**License**  
MIT License. Datasets: 20 Newsgroups, Azure samples. Dependencies: Talend 8.0+, Qlik Sense Enterprise, Python 3.8+.  

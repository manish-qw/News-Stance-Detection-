# News Stance Detection | Multi-Modal Classification System

## Project Overview
This project implements a **multi-modal classification system** for detecting stances in news articles.  
The system extracts text from news images, constructs semantic feature vectors, and classifies the stance of a headline with respect to its body text.  
It is designed to handle imbalanced datasets and improve robustness in real-world news classification tasks.

## Timeline
**Duration:** April 25 – May 25

## Key Contributions
- Built a **stance classification pipeline** using **OpenCV** and **OCR** to extract headlines and body text from news images.  
- Applied **TF-IDF vectorization** and **cosine similarity** on the imbalanced **FNC-1 dataset** to construct semantic feature vectors.  
- Boosted **minority class F1 score** from **0.03 to 0.52** using **Balanced Bagging**, **Logistic Regression**, and **Random Forest** with **SMOTE**.  
- Achieved **85% overall accuracy** and a **0.73 macro F1 score**, validating robustness on highly skewed data.  

## Skills & Technologies
- **Natural Language Processing (NLP), Multi-Modal Learning**  
- **Text Extraction (OCR, OpenCV)**  
- **Feature Engineering (TF-IDF, Cosine Similarity)**  
- **Machine Learning Algorithms (Logistic Regression, Random Forest, Ensemble Methods)**  
- **Imbalanced Data Handling (SMOTE, Balanced Bagging)**  
- **Model Evaluation (Accuracy, F1 Score, Macro F1)**  
- **Python, Scikit-learn**  

## Results
- Substantial improvement in **minority class detection**, addressing dataset imbalance.  
- Achieved high **macro F1 score (0.73)**, demonstrating balanced performance across all stance categories.  

## Future Work
- Explore **transformer-based architectures (e.g., BERT, RoBERTa)** for stance detection.  
- Incorporate **image-level features** alongside textual data for richer multi-modal learning.  
- Extend the model to handle **real-time news stream classification**.  

## References
- Fake News Challenge (FNC-1 Dataset)  
- SMOTE: Synthetic Minority Over-sampling Technique (Chawla et al., 2002)  
- Balanced Bagging for Imbalanced Classification (Lemaître et al., 2017)  

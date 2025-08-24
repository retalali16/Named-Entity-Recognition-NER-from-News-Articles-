# Named Entity Recognition (NER) with SpaCy & Streamlit

## Overview
This project implements **Named Entity Recognition (NER)** on news articles and user-provided text using **SpaCy**.  
The app allows you to compare two SpaCy models:

- **Small model** (`en_core_web_sm`) – lightweight and fast  
- **Transformer model** (`en_core_web_trf`) – more accurate and context-aware  

Entities detected include **PERSON, ORG, GPE, DATE, MONEY**, and more.

---

## Features
- Extract entities from user input or batch text files  
- Visualize entities using **color-coded highlights** (SpaCy displacy)  
- Compare SM vs TRF model outputs side-by-side  
- Show entity counts for each model  
- ]saved extracted entities to CSV

---


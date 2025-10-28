# hybrid-product-ai-classifier
Bilingual ML pipeline for e-commerce product normalization and classification (EN/BR, real + synthetic data)

**Author:** Ananias Araujo

---

## Overview (EN)

**Hybrid Product AI Classifier** is a professional project designed to normalize and categorize e-commerce product data. It combines **real and synthetic datasets** to simulate real-world scenarios and supports a **bilingual pipeline (EN/BR)**. The system leverages **Word2Vec embeddings + XGBoost classifier** for intelligent product categorization.

**Key Features:**
- Bilingual data preprocessing (English + Portuguese)
- Word2Vec embeddings for semantic understanding
- XGBoost classification baseline
- Product deduplication & clustering
- API + minimal UI for human-in-the-loop validation
- Modular, production-ready architecture

**Flow Diagram:**  

flowchart LR
A[Raw data: real + synthetic] --> B[Cleaning & preprocessing EN/BR]
B --> C[Word2Vec Embeddings]
C --> D[XGBoost Classifier]
D --> E[Validation & Metrics]
E --> F[API + Human Feedback Loop]
F --> G[Retraining]
G --> B


---

## Visão Geral (PT)

O **Hybrid Product AI Classifier** é um projeto profissional criado para normalizar e categorizar dados de produtos de e-commerce. Combina **datasets reais e sintéticos** para simular cenários próximos do mundo real, com pipeline bilíngue (EN + PT). O sistema utiliza **Word2Vec + XGBoost** para categorização inteligente e inclui uma interface minimalista para validação humana.

**Funcionalidades Principais:**
- Pré-processamento bilíngue de dados
- Embeddings Word2Vec para compreensão semântica
- Classificador XGBoost como baseline
- Deduplicação de produtos e clustering
- API + interface minimalista
- Arquitetura modular e pronta para produção

---

## Roadmap – Etapa 1

1. Setup repository (main protected, dev branch)  
2. Create folder structure + placeholder files  
3. Add `requirements.txt` for Python 3.11.x  
4. Create initial notebook `01_eda.ipynb`  
5. Add sample bilingual dataset (real + synthetic)  
6. Apply initial cleaning pipeline and generate WordClouds  
7. Create Kanban / issues for tasks  



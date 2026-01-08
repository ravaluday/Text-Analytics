**📰 Identifying Misinformation in Online News Articles**

**Fake News Classification Using NLP, Transformers & Web Deployment**

**📌 Overview**

This project focuses on detecting misinformation in online news articles using modern NLP techniques. It is built in two phases: baseline machine‑learning models and advanced transformer‑based architectures, culminating in a deployed web application for real‑time fake news detection.

**🚀 Phase 1: Baseline Fake News Classification**

Goal: Establish strong, interpretable baseline models.
Dataset: WELFake (~72,000 labeled news articles)
Key Steps:
- Text cleaning, normalization, and preprocessing
- TF‑IDF vectorization
- Baseline models: Logistic Regression and Naive Bayes
- Analysis of linguistic patterns and feature importance
These models provided a reliable foundation and helped identify core textual signals associated with misinformation.

**🤖 Phase 2: Transformer Models & Deployment**

Goal: Improve accuracy and build a practical, user‑facing solution.
Advanced Models:
- Lightweight Keras Transformer
- Fine‑tuned DistilBERT (best performance)
Deployment:
A Gradio web application was developed to enable:
- Real‑time fake news classification
- Headline‑article consistency checking
- A simple, business‑ready interface for end‑users

**🏁 Conclusion**

This project demonstrates a full NLP pipeline—from preprocessing and baseline modeling to transformer fine‑tuning and application deployment—showing how machine learning can be applied to combat misinformation at scale.

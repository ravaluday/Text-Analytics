**Topic: Identifying Misinformation in Online News Articles**

**Phase 1: Fake News Text Classification (Baseline Models)**

This project applies NLP techniques to classify online news articles as REAL or FAKE using the WELFake dataset (~72,000 articles). Phase 1 focused on data preprocessing and building baseline models. Text was cleaned and standardized, and TF-IDF with Logistic Regression and Naive Bayes were implemented to establish strong, interpretable baselines and understand key linguistic patterns.

**Phase 2: Transformer Models & Application Deployment**

In Phase 2, model performance was improved using a lightweight Keras Transformer and fine-tuned DistilBERT, achieving the best results. The project concluded with a Gradio web application for real-time fake news detection and headline-article consistency checking, demonstrating a practical, business-ready NLP solution.

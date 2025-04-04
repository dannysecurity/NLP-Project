# Overview
This project is aimed at classifying books into age-based audience categories: Child, Adolescent, Young Adult, and Adult. The model uses text excerpts to predict these labels based on both maturity level and reading difficulty.

The dataset was built from summaries and excerpts of public domain books, annotated using a custom rubric developed to capture thematic and linguistic complexity.

# Goals
- Automate audience rating using supervised machine learning.

- Improve content filtering and age-appropriate recommendations.

- Explore the intersection of rule-based annotation and modern NLP models.

# Methods
We experimented with multiple models:

- Logistic Regression (with TF-IDF & custom features)

- BERT (fine-tuned with [CLS] token representations)

- Ordinal Classifier (custom model for ordered labels)

- ELMo (contextual embeddings via TensorFlow Hub)

- Word Embeddings (using GloVe and Word2Vec)

# Files
- guidelines.pdf: Annotation criteria

- LogRegAP3.ipynb: Logistic Regression implementation

- BERTAP3.ipynb: BERT fine-tuning notebook

- WordEmbeddingsAP3.ipynb: Word embedding models

- ElmoAP3.ipynb: ELMo implementation

- AP3 Analysis.pdf: Model results & reflections

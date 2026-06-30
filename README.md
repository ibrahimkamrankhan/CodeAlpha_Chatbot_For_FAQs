# Chatbot for FAQs

A Natural Language Processing (NLP) conversational agent designed to match user queries against a predefined database of FAQs using semantic text similarity.

## Features
- **Text Vectorization:** Utilizes Term Frequency-Inverse Document Frequency (TF-IDF) to understand word distributions.
- **Intent Matching:** Measures query-to-FAQ similarity via Cosine Similarity matrices.
- **Fallback Guardrails:** Implements a strict confidence threshold (0.2) to accurately filter out irrelevant questions.

## Libraries Used
- `scikit-learn`
- `nltk`

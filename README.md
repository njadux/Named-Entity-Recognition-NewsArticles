# 🧠 Named Entity Recognition (NER) from News Articles

This project identifies **named entities** — people, organizations, and locations — from news articles using both **rule-based** and **model-based** approaches with **SpaCy**.

## 📘 Dataset
- **Source:** CoNLL-2003 (Kaggle)
- Focused on English news articles

## ⚙️ Tools & Libraries
- Python, Pandas, SpaCy
- SpaCy models: `en_core_web_sm` and `en_core_web_trf`

## 🧩 Approaches
1. **Rule-based NER:** Using SpaCy’s Matcher to extract entities based on patterns.  
2. **Model-based NER:** Using pre-trained SpaCy models for automatic entity recognition.

## 🖼️ Visualization
Used **Displacy** to visualize and highlight recognized entities directly within text.

## 📊 Results
- Compared results between `en_core_web_sm` (small) and `en_core_web_trf` (transformer) models.
- Transformer model achieved more accurate entity detection and context understanding.

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook/ner_conll003.ipynb

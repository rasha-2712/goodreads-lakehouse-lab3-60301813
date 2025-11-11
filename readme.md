# DSAI3202 - Lab 4: Text Feature Engineering on Azure

👩‍🎓 **Name:** Rasha Fadlalla  
🆔 **Student ID:** 60301813 
💻 **Lab:** Text Feature Extraction

---

## 🧠 Objective
To clean and process Goodreads reviews and extract text-based features such as:
- Review length
- Sentiment (positive, negative, compound)
- TF-IDF word importance
- BERT embeddings (semantic meaning)

---

## ⚙️ Steps Done
1. Loaded curated Gold dataset from Azure (`feature_v2/train`).
2. Cleaned text using regex and emoji removal.
3. Computed text length and sentiment features.
4. Generated TF-IDF and BERT embeddings.
5. Saved final dataset in the Gold Layer (`features_v2`).

---

## 📊 Features Summary
| Feature Name | Description |
|---------------|-------------|
| review_length_words | Number of words |
| review_length_chars | Number of characters |
| sentiment_pos | Positive score |
| sentiment_neg | Negative score |
| sentiment_compound | Polarity (−1 to +1) |
| bert_embedding | Semantic embedding |

---

## 📦 Requirements
You can install everything with:
```bash
pip install -r requirements.txt

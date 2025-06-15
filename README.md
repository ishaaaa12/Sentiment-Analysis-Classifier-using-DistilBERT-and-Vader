# Sentiment-Analysis-Classifier-using-DistilBERT and Vader

This project explores and compares different sentiment analysis techniques on a dataset of restaurant reviews. It builds three models—VADER, DistilBERT, and a hybrid of both—to classify reviews into three categories:

- 😠 **Negative**
- 😐 **Neutral**
- 🙂 **Positive**

---

## 📌 Project Highlights

- ✅ **VADER-based Model**  
  Rule-based sentiment scoring using the VADER lexicon  
  **Accuracy**: 76.5%

- 🤖 **DistilBERT-based Classifier**  
  Fine-tuned transformer model for contextual understanding  
  **Accuracy**: 82.3%

- 🔁 **Hybrid Model (VADER + DistilBERT)**  
  Combines VADER polarity scores with DistilBERT’s predictions  
  **Accuracy**: 85.4%

---

## 📂 Dataset

- 📄 **restaurant_reviews.csv**  
  A dataset containing labeled restaurant reviews with sentiments:
  - `negative` → 0  
  - `neutral` → 1  
  - `positive` → 2  

---

## 🛠️ Tech Stack

- [DistilBERT](https://huggingface.co/distilbert-base-uncased) (via 🤗 Transformers)
- VADER Sentiment Analyzer
- PyTorch
- scikit-learn
- pandas, matplotlib, seaborn



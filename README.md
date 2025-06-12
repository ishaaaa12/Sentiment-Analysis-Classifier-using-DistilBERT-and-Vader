# Sentiment-Analysis-Classifier-using-DistilBERT

This project builds a sentiment classification model using **DistilBERT** to classify restaurant reviews into one of three categories: **negative**, **neutral**, or **positive**.


## 🧠 Model Architecture

- **Base Model**: [DistilBERT](https://huggingface.co/distilbert-base-uncased)
- **Tokenizer**: `DistilBertTokenizerFast`
- **Classification Head**:
  - Linear → ReLU → Dropout → Linear
  - Output size: 3 (sentiment classes)

---

## 📂 Dataset

- Source: [`restaurant_reviews.csv`](https://raw.githubusercontent.com/kyuz0/llm-chronicles/main/datasets/restaurant_reviews.csv)
- Format: Text review and labeled sentiment
- Sentiments:  
  - `negative` → 0  
  - `neutral` → 1  
  - `positive` → 2

---



# transformer-chatbot-support
A customer support chatbot built using HuggingFace Transformers (DistilBERT/GPT-2).
# 🤖 Transformer-Based Customer Support Chatbot

A chatbot trained using the Transformer architecture (DistilBERT or GPT-2) to handle customer support queries. The model is fine-tuned on JSON-based QA pairs and deployed via Gradio for interactive use.

---

## 📌 Features

- Trained on 1000+ customer support Q&A pairs
- Uses DistilBERT or GPT-2 from HuggingFace
- Deployed with Gradio UI (or Flask optional)
- Fine-tuned on domain-specific queries
- Can handle reset passwords, order status, account info, etc.

---

## 🧠 Model Architecture

- Transformer: `DistilBERT` or `GPT-2` (you can choose)
- Tokenizer: HuggingFace pretrained tokenizer
- Fine-tuned with cross-entropy loss
- JSON-based question-answer training set

---

## 🗃️ Dataset Format

```json
[
  {"question": "How to reset my password?", "answer": "Click on 'Forgot Password' on the login page."},
  {"question": "Where is my order?", "answer": "Log in and check your order history."},
  ...
]

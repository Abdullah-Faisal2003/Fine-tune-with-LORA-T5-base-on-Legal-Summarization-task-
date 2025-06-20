# 🧠 Project Title: Legal and Product Text Summarization with LoRA-enhanced Transformers

## 📄 Overview

This project demonstrates two fine-tuning pipelines for abstractive text summarization using HuggingFace Transformers and the LoRA (Low-Rank Adaptation) technique for efficient training.

It includes:

1. **Legal Document Summarization**  
   - Uses the `google/flan-t5-base` model.  
   - Trained on the `legal_summarizer_data` dataset from HuggingFace.  
   - Incorporates LoRA to reduce memory usage while maintaining accuracy.

2. **Product Search Summarization (Query → Title)**  
   - Trains on a custom dataset of search queries and product titles.  
   - Reformulates search terms into more relevant product descriptions.

## 🚀 Technologies Used
- Transformers (`google/flan-t5-base`)
- HuggingFace Datasets
- PEFT (Parameter-Efficient Fine-Tuning)
- LoRA
- PyTorch
- Google Colab

## 🧪 Key Features
- Efficient training with LoRA.
- Text summarization tuned for legal and e-commerce domains.
- Dataset filtering and preprocessing included.
- Export-ready tokenizer and model.

## 📂 Project Structure
```
Task_summarization (2).ipynb    # Legal domain summarization using LoRA
Task_summarization_DOC.ipynb    # Product query-title summarization pipeline
```

## 🔧 How to Use
1. Clone the repository.
2. Run the notebooks in Google Colab.
3. Fine-tuned models can be exported or pushed to HuggingFace Hub.

If the notebook isnt loading due to renderring error here's a link to colab of thr notebook: https://colab.research.google.com/drive/1YA6_YQJa75RFznA8za_T0mXx6RjltSt2?usp=sharing

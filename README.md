# 🚀 NLP Task 5: Fine-Tuning BERT for POS Tagging & Chunking

## 📖 Overview
This project focuses on fine-tuning a transformer model (DistilBERT) for **Token Classification tasks**, specifically:
- Part-of-Speech (POS) Tagging
- Chunking (Phrase Detection)

The model is trained on the **CoNLL-2003 dataset** using Hugging Face Transformers.

---

## 🎯 Objectives
- Understand token classification using transformers
- Perform POS tagging and chunking
- Handle tokenization and label alignment
- Evaluate model using sequence-based metrics

---

## 🛠️ Technologies Used
- Python 🐍
- Hugging Face Transformers 🤗
- Datasets Library
- Evaluate (Seqeval)
- Google Colab / Jupyter Notebook

---

## 📂 Dataset
- **Name:** CoNLL-2003
- **Type:** Token Classification Dataset
- **Labels:**
  - Named Entity Tags (used for chunking-like task)
  - Examples: `B-PER`, `I-ORG`, `B-LOC`

---

## 🔄 Workflow Pipeline
Raw Data → Tokenization → Label Alignment → Model Training → Evaluation → Inference

---

## ⚙️ Model Details
- Model: `distilbert-base-uncased`
- Task: Token Classification
- Framework: Hugging Face Trainer API

---

## 🧪 Training Configuration
- Epochs: 2
- Batch Size: 8
- Learning Rate: 2e-5
- Evaluation Strategy: Per Epoch

---

## 📊 Evaluation Metrics
The model is evaluated using **Seqeval metrics**:
- Precision
- Recall
- F1 Score

---

## 🔍 Sample Inference
**Input:**
John works at Google in California

**Output:**
John → B-PER
Google → B-ORG
California → B-LOC

---

## ⚖️ POS Tagging vs Chunking

| Feature | POS Tagging | Chunking |
|--------|------------|----------|
| Level | Word-level | Phrase-level |
| Example | Noun, Verb | Noun Phrase (NP) |
| Complexity | Easy | Medium |

---

## ⚠️ Challenges Faced
- Aligning labels with subword tokens
- Handling special tokens (-100)
- Dataset loading issues
- Runtime crashes due to memory limits

---

## 💡 Key Learnings
- Transformer-based token classification
- Importance of label alignment
- Use of Hugging Face Trainer
- Evaluation using sequence metrics
- Difference between POS tagging and chunking

---

## 📌 Conclusion
This project demonstrates how transformer models like BERT can be effectively used for sequence labeling tasks such as POS tagging and chunking, achieving strong performance with contextual understanding.

---

## 🙏 Acknowledgment
Thanks to **Innomatics Research Labs**, trainers, and mentors for guidance and support throughout this task.

---

## 🔗 Submission Links
- GitHub Repository: (Add your link here)
- LinkedIn Post: (Add your link here)

---

## 📎 How to Run
1. Install dependencies:
2. 
---

## ⚖️ POS Tagging vs Chunking

| Feature | POS Tagging | Chunking |
|--------|------------|----------|
| Level | Word-level | Phrase-level |
| Example | Noun, Verb | Noun Phrase (NP) |
| Complexity | Easy | Medium |

---

## ⚠️ Challenges Faced
- Aligning labels with subword tokens
- Handling special tokens (-100)
- Dataset loading issues
- Runtime crashes due to memory limits

---

## 💡 Key Learnings
- Transformer-based token classification
- Importance of label alignment
- Use of Hugging Face Trainer
- Evaluation using sequence metrics
- Difference between POS tagging and chunking

---

## 📌 Conclusion
This project demonstrates how transformer models like BERT can be effectively used for sequence labeling tasks such as POS tagging and chunking, achieving strong performance with contextual understanding.

---

## 🙏 Acknowledgment
Thanks to **Innomatics Research Labs**, trainers, and mentors for guidance and support throughout this task.

---

## 🔗 Submission Links
- GitHub Repository: (Add your link here)
- LinkedIn Post: (Add your link here)

---

## 📎 How to Run
1. Install dependencies:pip install transformers datasets evaluate seqeval
 
2. Run the Jupyter Notebook step by step

---

## ⭐ Author
**Koyal Mandal**

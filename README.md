# 🧠 Text Summarization using BART (CNN/DailyMail + SAMSum)

This mini-project demonstrates **abstractive text summarization** using pre-trained transformer models such as **BART** and **T5**, fine-tuned on filtered subsets of the **CNN/DailyMail** and **SAMSum** datasets.  
It’s optimized to run within Google Colab GPU limits.

---

## 🚀 Features
- Dataset exploration and filtering (short articles and dialogues)
- Pre-trained model testing: GPT-2, T5, BART, and PEGASUS
- Fine-tuning `facebook/bart-large-cnn` on the SAMSum dataset
- Combined CNN/DailyMail + SAMSum training for better generalization
- Custom text summarization and evaluation using ROUGE metrics

---

## 🧩 Datasets Used
1. **CNN/DailyMail** – News article summarization  
2. **SAMSum** – Dialogue summarization  

Both datasets are loaded via the 🤗 `datasets` library and filtered to reduce article length for Colab-friendly training.

---
## ⚙️ Setup

1. Clone the repository
```bash
git clone https://github.com/suyogdhungana/abstract-text-summarizer.git
```
2. Navigate into the project directory
```bash
cd abstract-text-summarizer
```
3. Run the notebook in Jupyter or Colab
```bash
jupyter notebook abstractTextSummarization.ipynb
```
---

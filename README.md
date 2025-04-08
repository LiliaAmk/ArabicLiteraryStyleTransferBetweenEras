#  جسر اللغة | Linguabridge
**Arabic Literary Style Transfer Between Eras**

> Transform Arabic texts between Classical Islamic Arabic and Modern Standard Arabic using NLP, Machine Learning, and Large Language Models — a collaborative student project.

---

##  Project Overview

**Jisser al-Logha (جسر اللغة)** is a Natural Language Processing project that aims to bridge the stylistic gap between two major eras of the Arabic language:

- ️ **Classical Islamic Arabic** — elaborate, poetic, and rich in metaphors
-  **Modern Standard Arabic** — concise, clear, and accessible

We developed a system that automatically transforms text between these two styles while preserving its original meaning. The project involved building a synthetic parallel corpus, applying machine learning (LoRA fine-tuning), and designing a user-friendly interface.

---

##  Team Contributions

This project was developed by students from ENSIA as part of the Fall 2024 NLP module.

| Name                  | 
|-----------------------|
| **Lilia Ammar Khodja** |
| **Abderrahim Rezki**   | 
| **Lina Amdirt**        |
| **Bouziane Abdenour**  | 
| **Djamila Amani Hamza**| 

---

##  Core Features

###  Style Transfer Module
- Fine-tuned **Noon 7B LLM** using **LoRA** to convert Arabic text between classical and modern styles.

###  Corpus Building
- Created a **synthetic parallel corpus** (6.9k training pairs, 526 test pairs)
- Used OCR, ChatGPT-based paraphrasing, and manual corrections

### Semantic Search Engine
- Built using **SentenceTransformer** and **ChromaDB**
- Search for semantically similar classical/modern text pairs

###  Web Interface: Linguabridge
- Real-time style conversion
- Parallel corpus exploration with adjustable semantic similarity

---

##  Results

| Direction             | Style Accuracy | Fluency | Meaning Retention |
|----------------------|----------------|---------|--------------------|
| Modern ➝ Classical   | 2.38 / 3       | 2.25    | 1.85               |
| Classical ➝ Modern   | 2.40 / 3       | 2.24    | 2.00               |

- **BLEU Score**: ~0.22
- Strong **linguistic alignment** in root usage and POS distributions

---

##  Tech Stack

-  Hugging Face Transformers + Datasets
-  LLM: Naseej/noon-7b
-  LoRA Fine-Tuning
-  ChromaDB + SentenceTransformer
-  Gradio Web UI
-  Arabic-specific preprocessing tools

---

##  Future Work

- Expand corpus with expert-labeled texts
- Improve prompting strategies and data diversity ...

---

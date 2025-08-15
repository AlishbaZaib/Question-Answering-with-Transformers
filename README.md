# Question Answering with Transformers  

This project implements a **Question Answering (QA) pipeline** using state-of-the-art **Transformer models** from Hugging Face.  
Given any context, it can understand the text, interpret the question, and return the most relevant answer — all within seconds.  

---

## 📝 Overview  
A **Natural Language Processing (NLP)** project that uses **Hugging Face Transformers** to build an automated **Question Answering (QA) system**.  
The system takes a text passage as context and returns the most relevant answer to any given question, powered by the `distilbert-base-cased-distilled-squad` model.  

---

## 📌 Features 
- Accepts any **context passage** and **question**  
- Finds and extracts the **most accurate answer**  
- Uses **pretrained Transformer models** for high accuracy  
- Demonstrates **interactive CLI usage** for Q&A  

---

## 🛠 Tech Stack  
- **Python 3**  
- **Hugging Face Transformers**   
- **Datasets (SQuAD)** 
- **Evaluate**  

---

## 📦 Installation  
Make sure you have Python installed, then run:  
```bash
pip install transformers datasets evaluate

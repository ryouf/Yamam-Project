# Semantic Search Engine for Hadith

## Project Overview
This project is a **Semantic Search Engine** designed to retrieve Hadiths based on **meaning** rather than exact keyword matching.  
Using advanced **Natural Language Processing (NLP)** techniques, the system allows users to input an Arabic query and receive the most semantically relevant Hadiths.  
The goal is to make Hadith exploration smarter and more intuitive by understanding the **context and intent** of the user’s question.

---

## Model
The system is powered by **Sentence Transformers** to convert Arabic text into numerical vector embeddings.  
Each Hadith is transformed into a vector representation that captures its **semantic meaning**.  
When a user submits a query, the model:
1. Encodes the query into an embedding.
2. Compares it to all Hadith embeddings using **cosine similarity**.
3. Returns the top-matching Hadiths ranked by similarity score.

---

## Dataset
The dataset comprises collections of Hadith from six primary sources: 
- **Sahih Muslim**
- **Sahih Bukhari**
- **Sunan an-Nasa'i**
- **Sunan Abi Da'ud**
- **Sunan Ibn Majah**
- **Jami' al-Tirmidhi**
  
The data is presented in both Arabic and English, containing information about the source, chapter number, hadith number,
the text of the hadiths in Arabic and English, and chain indexes that trace the narrators of each hadith. 

---

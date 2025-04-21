# Automated Document Summarizer

This project focuses on generating short and meaningful summaries of long scientific abstracts using **Extractive Text Summarization** techniques. The summarizer is built using the **TextRank algorithm** and is applied to biomedical research data sourced from PubMed.

[Kaggle Link](https://www.kaggle.com/code/medhavitripathi/automated-document-summarizer)  
[Link to Dataset](https://www.kaggle.com/datasets/bonhart/pubmed-abstracts)

The dataset contains **abstracts of scientific articles** across multiple topics, including Deep Learning, Covid-19, Brain-Machine Interfaces, and more. This project specifically focuses on the **Deep Learning** subset for demonstration. 

---

## Project Structure

- **Data Preprocessing**:
  - Extracted abstract data from JSON structure
  - Combined sentence-level abstracts into full-text form
  - Cleaned and tokenized the abstracts for summarization

- **Exploratory Data Analysis (EDA)**:
  - Word count distribution of abstracts
  - WordCloud generation for common terms
  - Frequency plots of top keywords

- **Document Summarization using ML Algorithms**:
  - Used `sumy` library to apply **TextRank** (unsupervised extractive summarization)
  - Summarized each abstract into a 1–2 sentence version
  - Output saved as a CSV with article titles and summaries

- **Output Format**:
  - Title of the article
  - Compressed summary (extracted from key sentences)

---

## Technologies and Tools

- **Languages**: Python  
- **Libraries**: NLTK, Sumy, Pandas, NumPy, Matplotlib, WordCloud, Seaborn
- **Platform**: Kaggle

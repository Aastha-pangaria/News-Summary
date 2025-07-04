# BBC News Text Summarization

This project demonstrates multiple approaches to text summarization—including traditional extractive (TF-IDF), graph-based (TextRank via Sumy), and neural abstractive (BART)—on the BBC News Summary dataset.

## Overview

While this project may be a basic implementation, it significantly expanded my understanding of key NLP concepts such as **chunking**, **vectorization**, and **tokenization**. Working through these methods provided hands-on experience with both traditional and neural approaches to summarization, as well as practical skills in data preprocessing and evaluation.

## Dataset

- The dataset used in this project was obtained from Kaggle. It contains news articles and corresponding human-written summaries, making it ideal for exploring summarization techniques.

## Features

- **Data Loading & Preprocessing:** Efficiently loads and cleans BBC News articles and their summaries.
- **Chunking:** Splits large texts into manageable segments for processing.
- **Vectorization:** Applies TF-IDF and other vectorization techniques to represent text numerically.
- **Tokenization:** Breaks text into tokens for both traditional and neural models.
- **Traditional Extractive Summarization:** Uses TF-IDF and cosine similarity to rank and select key sentences.
- **Graph-based Summarization:** Implements TextRank using the Sumy library for extractive summarization.
- **Abstractive Summarization:** Utilizes the pre-trained BART model from Hugging Face Transformers to generate abstractive summaries.
- **Evaluation:** Compares generated summaries to reference summaries using ROUGE metrics.
- **Reproducible Output:** Summaries and comparisons are presented in Markdown tables for easy sharing and documentation.

## Requirements

Install dependencies with:
pip install -r requirements.txt

## Usage

1. **Prepare the Dataset:**
   - Place the BBC News Summary dataset in your Google Drive or local directory as required by the notebook.
2. **Open the Notebook:**
   - Launch the provided Jupyter notebook (`BBC_News_Summary.ipynb`) in Google Colab or Jupyter.
3. **Run All Cells:**
   - The notebook will:
     - Load and preprocess data
     - Perform extractive and abstractive summarization
     - Evaluate results using ROUGE

## Example Output

Below is a sample comparison of the original article, reference summary, and generated summaries from different methods:

![image](https://github.com/user-attachments/assets/f2827287-f65d-4b86-9a06-b2a45ec78c89)

## Key Learnings & Reflections

- Gained practical experience with **text chunking**, **vectorization** (TF-IDF), and **tokenization** for NLP tasks.
- Understood the differences and trade-offs between extractive and abstractive summarization.
- Improved skills in data preprocessing, model evaluation, and presenting results in a reproducible format.
- Learned best practices for structuring and documenting machine learning projects on GitHub[3].

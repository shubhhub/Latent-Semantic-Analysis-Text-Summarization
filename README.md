# Latent Semantic Analysis (LSA) Text Summarization

## Overview

This project implements Latent Semantic Analysis (LSA) for automatic text summarization. LSA is a technique that analyzes the relationships between terms and documents in a corpus to extract the underlying structure and identify key concepts. The summarization process involves preprocessing text, creating a term-document matrix, applying Singular Value Decomposition (SVD), and selecting top sentences to generate a concise summary.

## Features

- **Text Preprocessing:** Lowercasing, tokenization, and removal of unnecessary characters.
- **Term-Document Matrix (TDM):** Formation of TDM using TF-IDF vectorization.
- **Singular Value Decomposition (SVD):** Application of SVD to factorize the TF-IDF vector.
- **Text Summarization:** Selection of top sentences based on computed scores to generate a summary.

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Latent-Semantic-Analysis-Text-Summarization
   ```

2. **Run the main script:**
   ```bash
   python lsa_text_summarization.py
   ```
   Follow the prompt to enter the desired number of sentences for the summary.

## Author

- Shubh Garg
- [Your GitHub Profile](https://github.com/shubhhub)


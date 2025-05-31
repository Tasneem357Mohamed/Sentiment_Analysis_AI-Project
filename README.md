
# Sentiment Analysis Project Using AI Classification

## Overview

This project aims to build a sentiment analysis model that automatically classifies textual data—such as reviews and social media posts—into **positive**, **negative**, or **neutral** categories. The analysis is useful for understanding public opinion, enhancing customer experience, and identifying sentiment trends over time.

## Goals

- Automatically classify text into sentiment categories.
- Understand public opinion on topics, products, or brands.
- Improve customer experience by analyzing feedback.
- Track sentiment trends to guide business decisions and marketing strategies.

## Dataset

The dataset is stored in a CSV file: `sentimentdataset.csv`.

### Dataset Structure

| Column | Description |
|--------|-------------|
| `ID` | Unique identifier for each entry |
| `Text` | The textual content (e.g., reviews or posts) |
| `Source` | Origin of the text (e.g., website, Twitter) |
| `Topic` | Category or product/brand reference |
| `Label` | Sentiment label (positive, negative, neutral) |

**Dataset URL**: [Click to Access](https://drive.google.com/file/d/1wjHnt-xtuLjZkn1YorvrTvf5dEmjApZc/view?usp=sharing)

## Requirements

### Data Preprocessing

- Lowercasing text
- Removing punctuation and stopwords
- Text normalization (e.g., expanding slang)
- Stemming or lemmatization

### Feature Engineering

- **Bag-of-Words**
- **TF-IDF (Term Frequency–Inverse Document Frequency)**
- **Word Embeddings** (e.g., Word2Vec, GloVe)

### Model Selection

Choose from the following algorithms:
- Naive Bayes
- Support Vector Machines (SVM)
- Logistic Regression
- Recurrent Neural Networks (RNN) or Long Short-Term Memory (LSTM)

### Model Evaluation

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Load and preprocess the dataset
4. Train and evaluate the model
5. Visualize sentiment trends

## Mentor

**TA. Andrew Magdy**  
Email: [Andrew.magdy@cis.asu.edu.eg](mailto:Andrew.magdy@cis.asu.edu.eg)

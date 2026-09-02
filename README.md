
# BBC Hindi News Topic Modeling

A Natural Language Processing (NLP) project that uses **Latent Dirichlet Allocation (LDA)** to discover hidden topics in Hindi news articles from the BBC Hindi dataset.

## 📌 Project Overview

News websites publish articles across many categories, but manually organizing large collections of articles can be time-consuming.

This project applies **Topic Modeling** to automatically identify major themes present in Hindi news articles.

The project uses **LDA (Latent Dirichlet Allocation)** to analyze the article text and discover groups of words that frequently occur together, representing different topics.

## 🎯 Objectives

- Analyze a collection of Hindi news articles.
- Preprocess Hindi text for NLP analysis.
- Apply LDA-based topic modeling.
- Identify the major topics present in the dataset.
- Visualize the distribution of topics.
- Understand how NLP can be applied to Hindi-language news data.

## 📊 Dataset

The project uses a cleaned **BBC Hindi news articles dataset** containing Hindi news articles along with their categories.

The dataset includes article text and category information that can be used for analyzing the underlying topics in the news corpus.

## 🧠 Methodology

The project follows these main steps:

1. **Data Loading**
   - Load the BBC Hindi dataset using Pandas.

2. **Data Preprocessing**
   - Clean the article text.
   - Remove unnecessary characters and unwanted content.
   - Prepare Hindi text for topic modeling.

3. **Text Vectorization**
   - Convert the processed text into a numerical representation suitable for LDA.

4. **Topic Modeling**
   - Apply **Latent Dirichlet Allocation (LDA)**.
   - Extract the most important words associated with each topic.

5. **Topic Interpretation**
   - Examine the top words from each topic.
   - Assign meaningful names to the discovered topics.

6. **Visualization**
   - Visualize topic distributions to understand the presence of different topics in the dataset.

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **NLTK**
- **Jupyter Notebook**
- **LDA (Latent Dirichlet Allocation)**
- **Natural Language Processing (NLP)**

## 📁 Project Structure

```text
bbc-hindi-topic-modeling/
│
├── bbc_hindi/
│
├── bbc_hindi_articles_with_categories_cleaned.csv
│
├── bbc_hindi_topic_modeling.ipynb
│
├── requirements.txt
│
└── README.md

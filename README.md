# Legislative Bill Summaries Analysis

## Overview

This project applies natural language processing (NLP) techniques to analyze legislative bill summaries from the 118th U.S. Congress. By leveraging topic modeling and semantic similarity methods, we aim to uncover underlying themes and patterns that reveal the nature of current legislation. The analysis is particularly geared toward understanding the legislative landscape relevant to business and economic interests, which can support risk management, regulatory anticipation, and policy trend analysis.

## Objectives

The project consists of two main components:

1. **Topic Modeling**
   - Apply techniques such as Latent Dirichlet Allocation (LDA) or BERTopic.
   - Extract meaningful topics from the corpus of bill summaries.
   - Critically reflect on whether the topics match the official policy areas for the 118th Congress.
   - Evaluate the relevance of topics with respect to business and economic interests.
   - Compare the extracted themes to the broader legislative agenda.

2. **Semantic Similarity**
   - Compute cosine similarities between bill summaries using vector representations (e.g., TF-IDF, transformer-based embeddings).
   - Investigate whether bills associated with similar policy areas (e.g., Taxation, Environmental Protection) appear close in semantic space.
   - Identify insights or unexpected patterns emerging from the data.

## Dataset

The dataset, consisting of the legislative bill summaries scraped from Congress.gov, has been shared on Blackboard.

## Implementation Details

- **Environment and Dependencies:**  
  The Python environment includes libraries such as:
  - `pandas` and `numpy` for data manipulation.
  - `scikit-learn` for TF-IDF vectorization.
  - `gensim` and/or `BERTopic` for topic modeling.
  - `transformers` (or equivalent) for advanced embedding techniques.
  - `matplotlib` and `seaborn` for visualization.
  - Additional libraries might be used as necessary for web scraping, if applicable, and further analysis.

- **Processing Pipeline:**  
  The analysis workflow includes:
  1. Data loading and preprocessing
  2. Text cleaning and tokenization
  3. Vectorization (TF-IDF or transformer-based embeddings)
  4. Topic modeling (LDA/BERTopic)
  5. Semantic similarity computation via cosine similarity
  6. Visualization and interpretation of results

## Running the Project

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-repo/legislative-bill-analysis.git](https://github.com/EdoConti/nlp_assignment.git
   cd nlp_assignment
   ```

2. **Install Dependencies:**  
   Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute the Notebooks:**  
   - For Jupyter Notebook:
     ```bash
     jupyter notebook assignment.ipynb
     jupyter notebook assignment_p2.ipynb
     ```

4. **Review the Results:**  
   Visualizations and output logs will appear in the notebook or as output files, depending on your implementation.

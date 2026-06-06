<div align="center">
  <img src="images/Project_Banner.png" alt="Semantic Search System Banner" width="100%" />
</div>

<h1 align="center">🛒 Context-Aware Semantic Search for Flipkart Reviews</h1>

<p align="center">
  <a href="https://colab.research.google.com/drive/1JkNjYz4vSFck50ccEScJeVodCrEzVpCZ">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  </a>
</p>

## 💡 About The Project
Traditional keyword-based search engines often fail to capture the true *meaning* of a user's query. This project implements a robust **Semantic Search Engine** specifically tailored for e-commerce, using a real-world dataset of **Flipkart Product Reviews**. 

By leveraging state-of-the-art **Sentence Transformers**, the system converts text into high-dimensional vector embeddings. This allows it to understand context and retrieve the most relevant reviews based on meaning rather than exact word matches.

## 🚀 Key Highlights
- **Intelligent Discovery:** Matches complex, natural language queries (e.g., *"comfortable shoes for long runs"*) with the most relevant product reviews.
- **Advanced Embeddings:** Utilizes pre-trained NLP transformer models to generate dense vectors for both queries and review data.
- **Cosine Similarity:** Accurately ranks search results by calculating the mathematical distance between the query vector and review vectors.
- **End-to-End Pipeline:** Includes complete data preprocessing, exploratory data analysis (EDA), embedding generation, and search execution.

## 📊 Exploratory Data Analysis & Visualizations
Our analysis covers comprehensive EDA and embeddings visualization:

### 1. Data Distribution & Dashboards
<p align="center">
  <img src="images/eda_advanced_dashboard.png" width="80%">
  <img src="images/top_products_dashboard.png" width="80%">
</p>

### 2. Text Analysis & Wordclouds
<p align="center">
  <img src="images/eda_wordclouds.png" width="45%">
  <img src="images/wordcloud_by_rating.png" width="45%">
</p>

### 3. Embeddings & Model Evaluation
<p align="center">
  <img src="images/pca_2d_visualization.png" width="45%">
  <img src="images/rag_performance.png" width="45%">
</p>

## 🛠️ Built With
* **Python** 
* **SentenceTransformers** (Hugging Face)
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Similarity Computation)

## 💻 Getting Started

To run this project locally, follow these steps:

1. **Clone the repo**
   ```bash
   git clone https://github.com/m1n1v1rus/Semantic_Search_System___Flipkart_Reviews.git
   cd Semantic_Search_System___Flipkart_Reviews
   ```
2. **Install Dependencies**
   ```bash
   pip install sentence-transformers pandas scikit-learn numpy jupyter matplotlib seaborn
   ```
3. **Launch the Notebook**
   ```bash
   jupyter notebook Semantic_Search_System___Flipkart_Reviews.ipynb
   ```
   *Alternatively, you can run the project directly in your browser using the [Google Colab Link](https://colab.research.google.com/drive/1JkNjYz4vSFck50ccEScJeVodCrEzVpCZ) at the top of the page!*

## 🤝 Contributing
Contributions make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## 📄 License
Distributed under the MIT License.

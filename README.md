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

## 🛠️ Tech Stack
* Python 3.x
* sentence-transformers & transformers
* PyTorch
* Faiss (Vector Search)
* scikit-learn
* pandas & numpy
* matplotlib & scipy

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/m1n1v1rus/Semantic_Search_System___Flipkart_Reviews.git

# Navigate into project directory
cd Semantic_Search_System___Flipkart_Reviews

# Install requirements
pip install -r requirements.txt

# Run notebook
jupyter notebook Semantic_Search_System___Flipkart_Reviews.ipynb
```

## 🤝 Contributing
All contributions are welcome — bug fixes, feature enhancements, or documentation improvements!

Please give appropriate credit to the original author if you use or modify this tool in your own projects.

## 📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

## 👤 Author
**Ayush Mani**  
🔗 GitHub: [@m1n1v1rus](https://github.com/m1n1v1rus)

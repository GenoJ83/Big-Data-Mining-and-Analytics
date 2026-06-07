# Big Data Mining and Analytics

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-100%25-F37626?logo=jupyter)](https://jupyter.org/)

A comprehensive collection of practical exercises, assignments, and lecture notes covering key concepts in big data mining and analytics. This repository documents the journey through various data mining techniques, from association rule learning to clustering and sentiment analysis.

## 📚 Repository Structure
Big-Data-Mining-and-Analytics/
├── LECTURE NOTES AND PRACTICUM-20250911/ # Core course materials
├── Practical 6_Clustering_USL/ # Unsupervised learning: clustering
├── nltk_data/ # NLTK resources for NLP tasks
├── Assignment.ipynb # Assignment 1 notebook
├── Assignment2.ipynb # Assignment 2 notebook
├── ClassAssignment.ipynb # In-class assignment
├── Practical4_Association_Mining.ipynb # Association rule learning
├── Sentiment_Analysis.ipynb # Sentiment analysis with NLTK
├── Big Data Mining_Lecture 7.pptx # Lecture slides
├── HousingData.xlsx # Dataset for assignments
└── Practical 6_Clustering_USL.zip # Archived clustering materials

text

## 🎯 Key Topics Covered

| Topic | Techniques & Algorithms | Notebook |
|-------|------------------------|----------|
| **Association Mining** | Apriori, FP-Growth, Market Basket Analysis | `Practical4_Association_Mining.ipynb` |
| **Clustering (USL)** | K-Means, Hierarchical, DBSCAN | `Practical 6_Clustering_USL/` |
| **Sentiment Analysis** | Text preprocessing, VADER, NLTK | `Sentiment_Analysis.ipynb` |
| **Classification** | Decision Trees, k-NN, Evaluation metrics | Various assignments |
| **Regression** | Linear, Polynomial, Housing price prediction | `HousingData.xlsx` based notebooks |

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `nltk`, `matplotlib`, `seaborn`

### Installation

```bash
# Clone the repository
git clone https://github.com/GenoJ83/Big-Data-Mining-and-Analytics.git
cd Big-Data-Mining-and-Analytics

# Install core dependencies
pip install pandas numpy scikit-learn nltk matplotlib seaborn

# Download NLTK data (if running sentiment analysis)
python -c "import nltk; nltk.download('vader_lexicon'); nltk.download('punkt')"

# Skincare_Search_Engine
Information retrieval system for finding tailored skincare products

## SI 650/EECS 549 (Information Retrieval) - Final Project
Finding skincare and beauty products tailored to your unique needs can be a challenge. This code utilizes PyTerrier, SentenceTransformers, and Scikit-Learn to build various IR systems that provides tailored skincare recommendations based on user input. Models include BM25, Divergence from Poisson Hypothesis (DPH) hypergeometric weighting model, learning-to-rank (LTR) with RandomForestRegressor, and Semantic Search. The file also contains evaluation metrics, such as MAP and NDCG, to compare the performance of the various models.

## Set Up
### Dependencies
- `Python3.11`
[Installation information can be found here](https://www.python.org/downloads/release/python-3112/)
- `Java 11` or newer

### Installations
- `pip install python-terrier`
- `pip install -U sentence-transformers`
- `pip install -U numpy scipy scikit-learn`



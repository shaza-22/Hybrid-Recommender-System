# Hybrid Recommender System

This project builds a hybrid recommender system using product review data. It combines association-rule mining with text-based similarity methods to explore customer behavior and generate product recommendations.

The workflow is implemented in a Jupyter notebook and covers data loading, sampling, preprocessing, frequent itemset mining, association rules, TF-IDF feature extraction, and cosine-similarity-based recommendation logic.

## Project Goals

- Analyze product review data to identify useful recommendation patterns.
- Use association rules to discover relationships between products.
- Apply text similarity techniques to compare products using review content.
- Combine multiple recommendation signals into a hybrid recommender approach.

## Files

- `Hybrid_Recommender_System.ipynb` - main notebook containing the full recommender workflow.
- `data/Reviews.csv` - review dataset used by the notebook. This file is tracked with Git LFS because it is larger than GitHub's normal file limit.
- `requirements.txt` - Python dependencies needed to run the project.

## Setup

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Then open and run:

```bash
jupyter notebook Hybrid_Recommender_System.ipynb
```

## Notes

The notebook expects the dataset at `data/Reviews.csv`.

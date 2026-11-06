# Instagram Spam Detection

Minor project (individual) — Instagram fake/spam account detection using machine learning, built on Instagram profile-metadata features.

## Overview
This project classifies Instagram accounts as **fake/spam** or **genuine** using supervised ML models trained on account-level features (follower/following counts, bio length, profile picture presence, etc.).

## Project Structure
```
instagram-spam-detection/
├── notebooks/
│   └── instagram_spam_detection.ipynb   # EDA, preprocessing, model training & evaluation
├── docs/
│   └── (presentation / report goes here)
├── requirements.txt
└── README.md
```

## Approach
1. **Data loading** — train/test CSVs with account features and a `fake` label
2. **EDA** — class distribution, boxplots, feature correlation heatmap
3. **Preprocessing** — train/test split into features (`X`) and target (`y`)
4. **Modeling** — compares multiple classifiers, including Logistic Regression and KNN
5. **Evaluation** — accuracy/metrics comparison across models

## Tech Stack
- Python, pandas, numpy
- scikit-learn (Logistic Regression, KNN, etc.)
- matplotlib, seaborn (visualization)

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/instagram_spam_detection.ipynb
```

## Author
Yash Kharode — D Y Patil International University

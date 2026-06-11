🎬 Group Recommender Systems Project (MovieLens 100K)
Advanced implementation of user‑based collaborative filtering, group recommendation strategies, sequential recommendation models, diversification techniques, and counterfactual explanations using the MovieLens 100K dataset.
This project was completed as part of coursework at Tampere University and demonstrates end‑to‑end recommender‑system engineering.

⭐ Project Overview
This repository contains four major components, each building on the previous one.

1. User‑Based Collaborative Filtering
Loaded and explored the MovieLens 100K dataset

Implemented Pearson correlation for user similarity

Implemented rating prediction using neighborhood‑based CF

Designed a custom similarity function and justified its usefulness

Generated group recommendations using:

Average aggregation

Least misery aggregation

Proposed and implemented a disagreement‑aware group recommendation method

2. Sequential Group Recommendations
Designed and implemented a new sequential recommendation method inspired by:

Transition‑based modeling

Temporal preference patterns

Sequence‑aware group aggregation

Includes a short slide deck explaining the method and design choices.

3. Diverse Sequential Group Recommendations
Implemented a diversity‑enhancing strategy to avoid:

Repetitive recommendations

Popularity reinforcement

Narrow preference loops

Techniques used:

Intra‑list diversity

Coverage‑based diversification

Sequence‑aware novelty scoring

4. Counterfactual Explanations for Groups
Designed and implemented a counterfactual explanation generator that:

Removes selected items from user histories

Recomputes recommendations

Identifies minimal sets of items that change group suggestions

Ensures fairness by avoiding explanations based on a single user’s history

Includes a slide deck demonstrating the method.

🛠️ Tech Stack
Python

NumPy, Pandas, SciPy

Jupyter Notebooks

MovieLens 100K dataset

Custom implementations (no external recommender libraries)

📂 Repository Structure
Code
├── part1_user_cf/
├── part2_sequential/
├── part3_diversity/
├── part4_counterfactuals/
├── slides/
└── README.md
🎯 Key Skills Demonstrated
Recommender system design

Similarity metrics & prediction functions

Group preference aggregation

Sequential modeling

Diversity optimization

Counterfactual reasoning

Clean code & reproducible experiments

🚀 How to Run
Each part contains:

A Jupyter notebook with explanations

Python scripts for reproducibility

Instructions for running the code

Dataset note:
Download MovieLens 100K from the official source:
https://grouplens.org/datasets/movielens/
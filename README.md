# Relational Databases for Data Science — Homework 2

This project uses the **MovieLens 100K** dataset to demonstrate relational database design and point-in-time correctness for ML features.

## Contents

- `hw2_movielens_Kalashnikov_Mykola.ipynb` — main Google Colab notebook (EDA, ERD, PostgreSQL DDL, normalization, and temporal SQL queries).
- `hw2_erd.png` — ER diagram.
- `hw2_schema.dbml` — editable ER diagram source.
- `hw2_schema.sql` — PostgreSQL schema.

## How to Run

1. Open `hw2_movielens_Kalashnikov_Mykola.ipynb` in Google Colab.
2. Use a Python 3.12 runtime (tested with Colab runtime 2026.07).
3. Run all cells. Required dependencies and PostgreSQL 16 are initialized in the notebook.

The MovieLens dataset is downloaded automatically.

**Dataset:** [MovieLens 100K — GroupLens](https://grouplens.org/datasets/movielens/100k/)
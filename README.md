# 🧠 Machine Learning Mini-Projects: Apriori & CAH

## 📌 Overview

This repository includes two unsupervised machine learning projects that explore different techniques for discovering patterns and groupings in datasets:

1. **Apriori Algorithm** – applied to a movie dataset to find frequent itemsets and association rules.
2. **CAH (Classification Ascendante Hiérarchique)** – used on a cheese dataset to identify hierarchical clusters of similar items.

---

## 🎬 Project 1: Apriori – Movie Dataset

### 🔍 Description

The Apriori project explores associations between items in a movie transaction dataset. Each row represents a set of movies watched together by a user. The project applies the Apriori algorithm to detect frequently co-occurring movie sets and derive association rules.

### 🎯 Objectives

- Convert raw data into a format suitable for transactional analysis.
- Identify frequent itemsets using the **Apriori algorithm**.
- Generate association rules based on metrics like **support**, **confidence**, and **lift**.
- Visualize relationships between movies using graph-based representation.

### 🛠 Tools and Libraries

- **Pandas & NumPy** – for data loading and manipulation
- **apyori** – to implement the Apriori algorithm
- **Matplotlib** – for visualizations
- **NetworkX** – to represent association rules as interactive graphs

### 📈 Outcomes

- Discovered meaningful associations (e.g., movies often watched together).
- Derived actionable rules from the data.
- Represented rules as a network for better visual interpretation.

---

## 🧀 Project 2: CAH – Fromage Dataset

### 🔍 Description

This project uses hierarchical clustering (Classification Ascendante Hiérarchique) to analyze a dataset containing nutritional information on different types of cheese. The aim is to group similar cheeses and visualize their relationships using a dendrogram.

### 🎯 Objectives

- Conduct exploratory data analysis and descriptive statistics.
- Understand relationships between features using visual exploration.
- Apply **hierarchical clustering** to form natural groups.
- Visualize the cluster structure using a dendrogram.

### 🛠 Tools and Libraries

- **Pandas & NumPy** – for data preparation and numerical analysis
- **Scipy** – for computing hierarchical clustering and linkage matrices
- **Matplotlib** – to visualize the dendrogram
- **fcluster** – to extract flat clusters from the hierarchical tree

### 📈 Outcomes

- Grouped cheeses into clusters based on nutritional similarity.
- Generated a dendrogram to display the hierarchical structure.
- Interpreted cluster characteristics for analytical insights.

---

## 🧪 Technologies Summary

| Project     | Core Algorithm | Key Libraries Used                              |
|-------------|----------------|--------------------------------------------------|
| Apriori     | Association Rule Mining | apyori, pandas, networkx, matplotlib |
| CAH         | Hierarchical Clustering | scipy, pandas, matplotlib              |

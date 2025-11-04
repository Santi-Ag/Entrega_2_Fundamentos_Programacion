# Entrega_2_Fundamentos_Programacion
Exploratory RNA-seq analysis using Python. Includes data loading, preprocessing, and visualization with histograms, boxplots, heatmaps, PCA, and barplots. Uses pandas, seaborn, and scikit-learn to explore gene expression patterns across treatments and genotypes.
Here’s a clean **README.md** draft for your GitHub repository:

---

# 🧬 RNA-seq Exploratory Analysis

This repository contains a Python-based exploratory analysis of RNA-seq normalized expression data.
The project demonstrates how to visualize and interpret gene expression patterns using multiple approaches.

## 📘 Overview

The analysis includes:

* **Data preprocessing** with `pandas` and `numpy`
* **Visualization** using `seaborn` and `matplotlib`
* **Dimensionality reduction (PCA)** with `scikit-learn`
* **Correlation analysis** and hierarchical clustering
* **Exploration of gene expression** across tissues, genotypes, and treatments

## 📊 Visualizations

* Global expression **histogram**
* Per-sample **boxplot**
* **Heatmap** of sample correlations
* **PCA scatter plot** by treatment/genotype
* **Barplot** of top expressed genes

## 🧩 Data

The dataset (`GSE304212_normalized_counts.xlsx`) includes normalized RNA-seq expression counts from different mouse tissues and conditions.

## 🛠️ Requirements

```bash
pip install pandas numpy seaborn matplotlib scikit-learn scipy openpyxl
```

## 🚀 Run the analysis

```bash
python GSE304212_analysis.py
```

## 📄 License

This project is open-source and available under the MIT License.

---

Would you like me to shorten it so it fits GitHub’s **README preview (about 500–600 chars)** or keep it in full detailed form?

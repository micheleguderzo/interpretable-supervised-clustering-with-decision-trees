# Implementation and Validation of a Decision Tree-Based Approach for Interpretable Supervised Clustering – Thesis

![Language](https://img.shields.io/badge/code-python-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?logo=open-source-initiative)
![Status](https://img.shields.io/badge/status-finished-success?style=flat&logo=github)

This repository contains the Bachelor's thesis project developed at the **Department of Statistical Sciences, University of Padua**, during the academic year **2024/2025**.

## 📌 Project Overview

The goal of this project is to develop an **interpretable supervised clustering algorithm** based on decision trees. The proposed method, called **Best Node Selection**, iteratively identifies the most representative and pure nodes within decision trees, using the **Fβ-score** as the selection criterion.

The analysis aims to show how this approach can generate structured and explainable clusters, balancing accuracy and interpretability in classification-based clustering tasks.

## 🧠 Key Topics

- Supervised clustering using decision trees  
- Fβ-score metric for evaluating node quality  
- Iterative node selection and pruning  
- Exploratory data analysis and correlation analysis  
- Trade-offs between cluster purity and representativeness  
- Implementation and evaluation in Python using Jupyter and scikit-learn

## 🗂️ Repository Structure

├── README.md     # This file  
├── LICENSE       # Project license (MIT)  
├── .gitignore    # Git ignore file for excluded files/folders  
├── code/         # Python script implementing the Best Node Selection algorithm and evaluation  
├── plots/        # Output plots and visualizations used in the thesis  
└── report/       # Final thesis report (PDF written in LaTeX)

## 📊 Dataset

The dataset used is the **Breast Cancer Wisconsin (Diagnostic)** toy dataset provided by [scikit-learn](https://scikit-learn.org/stable/datasets/toy_dataset.html). It contains **569 observations** of **30 numeric features** derived from digitized images of fine needle aspirate (FNA) of breast masses. Each observation is labeled as either **Benign** or **Malignant**, and features include measurements such as radius, texture, perimeter, area, and more.  

## 🛠 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- scikit-learn  
- Graphviz  
- Jupyter Notebook  
- LaTeX  

## ⚠️ Notes on GitHub Visualization

Due to GitHub's limitations in rendering Jupyter Notebooks, some special characters in the decision tree visualizations generated with Graphviz (e.g., the symbol `≤`) may appear incorrectly encoded (e.g., `\xe2\x89\xa4` instead of `≤`).

To correctly view the decision tree diagrams:

- Open the notebook locally using **Jupyter Notebook** or **Visual Studio Code**
- **Or**, view the correctly rendered diagrams saved as image files in the [`plots/`](plots/) folder of this repository

## 📄 Final Report

You can read the full report with methodology, analysis, and conclusions in [`report/final_report.pdf`](report/final_report.pdf).

## 👤 Author

**Michele Guderzo**  

## 📝 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

*This project was developed for educational purposes only.*

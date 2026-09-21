# Extended Explainable Hybrid Ensemble Framework

This repository contains the source code, datasets, and experimental pipeline for the **Extended Explainable Hybrid Ensemble Framework**. The project benchmarks 15 machine learning models across three public datasets, focusing on performance, explainability, and reliability.

## Overview

The framework evaluates a diverse set of models, including linear models, tree-based ensembles, deep learning architectures, and retrieval-augmented models. The core of the study is the **Reliability-Aware Model Selection (RAMS)** methodology, which integrates traditional performance metrics with explanation stability and concordance to select the most trustworthy models.

## Data Availability

This study used three publicly available datasets. The IBM Telco Customer Churn dataset was originally distributed as an IBM sample dataset and is accessible through the Kaggle mirror (https://www.kaggle.com/datasets/blastchar/telco-customer-churn) under the original IBM terms; the identical dataset was also cross-verified against the IBM GitHub sample repository. The Statlog German Credit dataset was obtained from the UCI Machine Learning Repository (ID 144, https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data, doi: 10.24432/C5NC77) under a Creative Commons Attribution 4.0 International (CC BY 4.0) license. The Superstore Sales dataset was obtained from Kaggle (https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) under a CC0 Public Domain license. All three datasets were used strictly for academic benchmarking. No personally identifiable information was accessed. The exact preprocessing pipeline, train–test splits, and random seeds required to reproduce every table and figure in this paper are provided with the source code.

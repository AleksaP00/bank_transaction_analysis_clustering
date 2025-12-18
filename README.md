# Customer Segmentation: RFM Analysis & Clustering

## 📌 Overview
Comprehensive customer segmentation project analyzing banking transaction data using RFM methodology combined with machine learning clustering techniques.

## 🎯 What This Project Does
1. **Data Processing**: Merges transaction and client data, creates pivot tables
2. **RFM Analysis**: Segments customers based on Recency, Frequency, Monetary value
3. **Clustering**: Applies K-Means and Hierarchical clustering
4. **Optimization**: Compares SSE vs Silhouette methods for optimal clusters
5. **Visualization**: Includes dendrograms, elbow plots, and cluster profiles

## 📊 Key Features
- **RFM Scoring**: 5 customer segments based on transaction behavior
- **Dual Normalization**: StandardScaler and MinMaxScaler comparison
- **Multiple Clustering**: K-Means (optimized two ways) + Hierarchical
- **Outlier Detection**: Identifies and handles extreme values
- **Cluster Profiling**: Detailed description of each customer segment

## 🚀 Quick Start
1. **Download data**: https://drive.google.com/drive/folders/1weF8z0NjVxQxrUDcLisinkN8cVrIcaD8?usp=sharing
2. **Place in `data/` folder**: `trans.csv` and `client_accounts.csv`
3. **Run**: `bank_transaction_analysis_clustering.ipynb` in Jupyter

## 🔧 Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

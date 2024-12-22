# Clustering Project

## Overview
This project implements **K-Means Clustering** for customer segmentation using a dataset with categorical and numerical features. The focus is on data preparation, algorithm selection, and clustering performance evaluation.

---

## Key Steps
### Data Preparation
- Applied feature engineering techniques:
  - **One-Hot Encoding** for categorical variables (`BRAND NAME`, `SUPPLIER`).
  - Dimensionality reduction to analyze variance.

### Model Selection
- Chose **K-Means Clustering** for its efficiency with large datasets and simplicity in implementation.

### Evaluation Metrics
- **Calinski-Harabasz Score**: Higher values indicate better-defined clusters.
- **Davies-Bouldin Index**: Lower values indicate better clustering quality.

Based on these metrics, the optimal number of clusters was determined to be **2**.

---

## Challenges and Solutions
### Challenges
1. Lack of domain knowledge complicated dataset understanding.
2. The `description` column contained unstructured information, making preprocessing difficult.

### Solutions
1. Used correlation techniques to simplify data relationships.
2. Applied **Pearson Correlation** to identify significant features effectively.

---

## Results
- Successfully implemented clustering with **2 clusters**, achieving optimized evaluation metric scores.

---

## Key Learnings
- The importance of feature engineering and iterative evaluation in clustering success.
- Domain knowledge enhances preprocessing and feature selection.

---

## Usage Instructions
1. **Dataset Preparation**:
   - Use one-hot encoding for categorical columns like `BRAND NAME` and `SUPPLIER`.
   - Clean and preprocess text columns.
2. **Running the Model**:
   - Apply dimensionality reduction for variance analysis.
   - Use the K-Means algorithm with varying `K` values.
   - Evaluate clusters using the Calinski-Harabasz Score and Davies-Bouldin Index.
3. **Interpreting Results**:
   - Select the `K` value with optimal evaluation metrics.

---

## Future Improvements
- Incorporate domain knowledge for enhanced feature selection.
- Experiment with advanced clustering techniques like DBSCAN or hierarchical clustering.
- Automate feature engineering for complex datasets.
- Visualize clusters for better interpretability.

---

## License
This project is open-source and available under the [MIT License](LICENSE).


# Warehouse and Retail Sales - Customer Segmentation

## Overview
This project performs **unsupervised clustering** on customer records from a warehouse and retail sales database. The goal is to segment customers into clusters based on their purchasing behaviors, enabling the business to:
- Optimize the significance of each customer.
- Modify products according to distinct needs and behaviors.
- Address concerns specific to different types of customers.

---

## Key Steps
### Data Preparation
- **Libraries Used**:
  - `Pandas`, `NumPy` for data manipulation.
  - `Matplotlib`, `Seaborn` for visualization.
  - `scikit-learn` for clustering algorithms.
- Removed unnecessary columns: 
  - Dropped `ITEM DESCRIPTION`, `QUANTITY`, `STD UNIT`, `NUMBER UNIT`, and unnamed columns for data cleaning.
- Applied **One-Hot Encoding** to preprocess categorical variables.

### Clustering Algorithm
- Implemented **unsupervised clustering** using techniques like K-Means for customer segmentation.

---

## Results
- Successfully segmented customers into distinct clusters based on their purchasing behavior.

---

## Challenges
1. Large volume of unstructured data requiring significant preprocessing.
2. Identifying key features for clustering without domain expertise.

### Solutions
- Applied feature engineering to preprocess data and improve clustering accuracy.

---

## Visualizations
- Used `Matplotlib` and `Seaborn` to generate insights and analyze the cluster distribution.

---

## Future Enhancements
- Use advanced clustering algorithms like DBSCAN or hierarchical clustering for better results.
- Incorporate domain-specific knowledge to improve data preprocessing.
- Automate the pipeline for larger datasets.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

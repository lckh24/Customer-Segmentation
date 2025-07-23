# Customer Segmentation using Machine Learning

This project applies unsupervised learning techniques to segment customers based on their financial and behavioral attributes. The goal is to help businesses better understand their customers and personalize marketing strategies.

---
## Project Workflow

1. **Data Loading**
   - Read dataset using `pandas`
2. **Data Preprocessing**
   - Drop missing, duplicate, and empty columns
   - Reset index
3. **Feature Scaling**
   - Standardization using `StandardScaler`
4. **Dimensionality Reduction**
   - Apply PCA for 2D visualization
5. **Clustering**
   - Segment customers using `KMeans`
   - Evaluate cluster quality (Elbow/Silhouette method)
6. **Feature Importance**
   - Use `XGBoost` to identify features that define each cluster
7. **Visualization**
   - Plot cluster distributions and PCA projections using `matplotlib` and `seaborn`

---

## Key Algorithms

### PCA (Principal Component Analysis)
- Reduces high-dimensional data to 2D space for visualization and noise reduction.

### KMeans Clustering
- Groups customers into distinct clusters based on behavior.
- Optimal number of clusters selected using the Elbow Method.

### XGBoost Classifier
- Trained on clustering results to evaluate which features are most predictive of group membership.
- Offers insight into which attributes most affect customer segmentation.

---

## Outputs

- PCA visualization of clusters
- Feature importance bar charts
- Segment profile analysis for business recommendations

---

## 🧑‍💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation

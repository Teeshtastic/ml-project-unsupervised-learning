# Project Description

In this project, I applied unsupervised learning techniques to a wholesale customer dataset and used data visualization tools to communicate insights for business decision-making.

---

## Project Tasks

**Exploratory Data Analysis & Pre-processing:**
- Import and examine the dataset
- Analyze spending distributions and correlations between product categories
- Detect outliers using box plots
- Apply robust scaling to handle extreme values in the data

**Unsupervised Learning Techniques:**
- **K-means clustering:** Use the elbow method to determine optimal clusters
- **Hierarchical clustering:** Use dendrogram analysis for cluster validation
- **Principal Component Analysis (PCA):** Identify key variance drivers and reduce dimensionality

---

## Dataset Information

- **Size:** 440 customers × 8 features  
- **Features:** Channel, Region, Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicassen  
- **Target:** Identify customer segments based on spending patterns

---

## Key Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (KMeans, PCA, RobustScaler)  
- SciPy (Hierarchical Clustering)

---

## Major Findings

- **Customer Segmentation:**  
  - Channel 1 (restaurants/hotels) focus on Fresh products  
  - Channel 2 (retail stores) focus on Grocery, Milk, and Detergents  

- **Geographic Distribution:**  
  - Region 3 dominates with 72% of customers  
  - Expansion opportunities in Regions 1 & 2  

- **PCA Results:**  
  - 3 components explain 80% of variance  
  - Achieves 50% dimensionality reduction  

- **Clustering:**  
  - Both K-means and hierarchical clustering confirm 3 optimal customer segments with clear business interpretations

---

## Business Impact

The analysis enables targeted marketing strategies, identifies geographic expansion opportunities, and provides data-driven customer segmentation for improved business decision-making.
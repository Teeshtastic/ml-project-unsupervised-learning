#Project Description

In this project, I applied unsupervised learning techniques to a wholesale customer dataset and use data visualization tools to communicate insights for business decision-making.

#Project Tasks:
Exploratory Data Analysis & Pre-processing: Import and examine the dataset, analyze spending distributions and correlations between product categories, detect outliers using box plots, and apply robust scaling to handle extreme values in the data.

#Unsupervised Learning: Implement three key techniques:

-K-means clustering using elbow method to determine optimal clusters
-Hierarchical clustering with dendrogram analysis for cluster validation
-Principal Component Analysis (PCA) to identify key variance drivers and reduce dimensionality

#Dataset Information

Size: 440 customers × 8 features
Features: Channel, Region, Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicassen
Target: Identify customer segments based on spending patterns

#Key Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
Scikit-learn (KMeans, PCA, RobustScaler)
SciPy (Hierarchical Clustering)

#Major Findings

Customer Segmentation: Two distinct channels - Channel 1 (restaurants/hotels) focus on Fresh products, Channel 2 (retail stores) focus on Grocery/Milk/Detergents
Geographic Distribution: Region 3 dominates with 72% of customers, presenting expansion opportunities in Regions 1 & 2
PCA Results: 3 components explain 80% of variance, achieving 50% dimensionality reduction
Clustering: Both K-means and hierarchical clustering confirmed 3 optimal customer segments with clear business interpretations

#Business Impact
The analysis enables targeted marketing strategies, identifies geographic expansion opportunities, and provides data-driven customer segmentation for improved business decision-making.
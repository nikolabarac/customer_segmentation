# Customer Segmentation Project

## 📚 Project Overview
Customer segmentation is the process of dividing customers into distinct groups based on shared characteristics, behaviors, or demographics. This approach helps businesses understand their customers better and tailor their marketing strategies more effectively.

In this project, I used unsupervised learning techniques to segment customers based on various attributes and provide actionable insights to help the marketing team refine their strategies.

## 🧠 Goal
The goal of this project is to apply clustering algorithms to segment customers into meaningful groups and offer recommendations on how the marketing team can target these segments effectively.

## 🔧 Tools & Techniques Used
This project leverages several machine learning techniques:
- **KMeans**
- **Gaussian Mixture Models (GMM)**
- **Affinity Propagation**
- **Mean Shift**

Additionally, I utilized **Silhouette Score** to assess the quality of clusters and determine the best combination of variables for customer segmentation.

After evaluating these models, I chose the best set of features and the optimal clustering algorithm based on the silhouette score.

### Insights & Recommendations
After visualizing the clusters, I used graphical methods to identify meaningful patterns and recommend targeted strategies. The marketing team can use the segmentation to:
- Narrow their marketing campaigns
- Design promotions targeting specific customer groups
- Enhance customer engagement and satisfaction

### Final Recommendations Table

The table below summarizes the identified customer segments, with relevant thresholds for **Annual Income** and **Spending Score**:

| **Cluster** | **Annual Income** | **Spending Score** |
|-------------|-------------------|--------------------|
| **Cluster 1** | ≤ 40              | ≤ 40               |
| **Cluster 2** | ≤ 40              | ≥ 60               |
| **Cluster 3** | ≥ 70              | ≤ 40               |
| **Cluster 4** | ≥ 70              | ≥ 60               |
| **Cluster 5** | 40–70             | 40–60              |

These clusters provide actionable insights to guide marketing campaigns and maximize customer engagement.
![Cluster Plot](https://github.com/nikolabarac/customer_segmentation/blob/master/customer_segmentation.png)


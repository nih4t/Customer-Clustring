# Customer-Clustring

![CustomerImage](https://github.com/nih4t/Customer-Clustring/assets/82613166/b69cffe9-c53b-463c-b842-94e270ceffe7)


Welcome to the Customer Clustering project repository! This project focuses on clustering customers based on their Annual Income and Spending Score using two popular clustering algorithms: Hierarchical Clustering and K-Means Clustering.

## Dataset

The dataset for this project contains the following attributes:

- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

For the purpose of this project, we are focusing solely on the attributes "Annual Income (k$)" and "Spending Score (1-100)" to perform customer clustering.

# Result
## Clustering Algorithms

### Hierarchical Clustering

In the Hierarchical Clustering algorithm, we used a distance-based approach to group customers into clusters. After analyzing the results, we obtained 5 clusters:

![Hierarchical Clustering](https://github.com/nih4t/Customer-Clustring/assets/82613166/203a8377-fb7e-486f-98cb-b0a46a7755f3)

1. Cluster 1: Low spending score and high annual income
2. Cluster 2: Middle annual income and spending score
3. Cluster 3: High spending score and high annual income
4. Cluster 4: High spending score and low annual income
5. Cluster 5: Low spending score and low annual income

### K-Means Clustering

The K-Means Clustering algorithm also grouped customers into 5 clusters based on their similarity:

![K-Means Clustering](https://github.com/nih4t/Customer-Clustring/assets/82613166/090c21b1-095e-4b24-a1ef-ef0fc62a08d3)


1. Cluster 1: Middle annual income and spending score
2. Cluster 2: High annual income and spending score
3. Cluster 3: High spending score and low annual income
4. Cluster 4: Low spending score and high annual income
5. Cluster 5: Low spending score and low annual income

The application of Hierarchical Clustering and K-Means Clustering algorithms on the customer dataset yielded insightful results that provide a deeper understanding of customer behavior and characteristics. The Hierarchical Clustering algorithm identified five distinct customer segments based on their spending patterns and annual income. This segmentation provides valuable information for targeted marketing strategies. On the other hand, the K-Means Clustering algorithm also produced five clusters, aligning with the Hierarchical Clustering results to a large extent. These clusters enable businesses to tailor their offerings to different customer groups effectively. By analyzing and comparing the results of both algorithms, businesses can make data-driven decisions to enhance customer engagement, optimize marketing efforts, and personalize services based on specific customer needs and preferences.

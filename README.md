# 3730-Customer-Segmentation
Customer segmentation project for CSC 3730
**Group 6**
**Hammaad Alam, Nick Jaramillo, Fahd Khattak, Damien Nguyen, Madison Nguyen, Taylor Wall, Demetri Williams**


**Model Comparison**
To check that the K-means segments are stable and not just a result of one algorithm, we compare them against a second clustering method.

**Method**: Agglomerative (hierarchical) clustering on the same standardized RFM features, using the same number of clusters (k) selected for K-means
- **Agreement metric**: Adjusted Rand Index (ARI), where 1 means identical groupings and values near 0 mean no agreement beyond chance
- **Segment overlap**: A crosstab of K-means labels vs. agglomerative labels shows which customer segments match across both methods and which ones differ

If both methods produce similar segments, it supports that the customer groups reflect real purchasing patterns.

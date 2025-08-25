**Customer Segmentation Comparison: KMeans vs Hierarchical Clustering**
📌 Project Overview

This repository demonstrates Customer Segmentation using two clustering
algorithms:
1. KMeans Clustering
2. Agglomerative (Hierarchical) Clustering

Both are applied on the Mall Customers dataset, where customers are
grouped based on Annual Income and Spending Score.

------------------------------------------------------------------------

🔍 Algorithm Comparison

-   KMeans Clustering:
    -   Centroid-based algorithm.
    -   Fast and scalable for large datasets.
    -   Requires choosing k (number of clusters).
-   Hierarchical Clustering:
    -   Tree-based (builds a hierarchy of clusters).
    -   Dendrogram helps to decide cluster count.
    -   Computationally heavier for large datasets.

------------------------------------------------------------------------

📊 Business Decisions for Each Cluster

-   VIP Customers (most valuable 💎)
    -   Premium services, loyalty programs, exclusive discounts.
    -   Keep them happy → major revenue source.
-   Inactive Customers (low spenders 🚫)
    -   Don’t spend big marketing budget.
    -   Maybe low-cost offers (oil change, free car wash).
    -   If no response → ignore to save money.
-   Balanced Customers ⚖️
    -   Steady income.
    -   Cross-sell maintenance add-ons (battery check, filters).
    -   Base revenue customers.
-   Saver Customers (want to save 💰)
    -   Attracted by discounts/coupons.
    -   Upsell affordable bundles.
    -   Not interested in luxury services.
-   Spender Customers 🛒
    -   Spend a lot but not always rich.
    -   Personalized deals, limited-time offers.
    -   Can be converted into VIPs if nurtured.

------------------------------------------------------------------------

📂 Files Included

-   kmeans_customer_segmentation.ipynb → KMeans clustering
    implementation.
-   hierarchical_customer_segmentation.ipynb → Agglomerative clustering
    implementation.
-   requirements.txt → Required dependencies.
-   K-Means VS Hierarchical plot.png →  For comparing the results of both the algorithms.
------------------------------------------------------------------------

👨‍💻 Author

Saifullah Umar
- 📍 BS Artificial Intelligence Student at Nutech University Islamabad, Pakistan.
- 🔗 GitHub: https://github.com/SaifUllahUmar0317
- 📧 Contact: saifpakistani0317@gmail.com

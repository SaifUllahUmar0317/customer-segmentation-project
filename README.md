🛍️ Customer Segmentation using K-Means & Hierarchical Clustering

📌 Project Overview

This project applies unsupervised machine learning algorithms to segment
mall customers based on their annual income and spending score.

By grouping customers into different clusters, businesses can better
understand their customers and make data-driven marketing decisions.

------------------------------------------------------------------------

📊 Algorithms Used

1️⃣ K-Means Clustering

-   Divides data into K groups based on proximity to centroids.
-   Works best for large datasets.
-   Faster and more scalable than hierarchical methods.

2️⃣ Hierarchical Clustering (Agglomerative)

-   Builds a dendrogram tree to visualize merging of clusters.
-   Does not require predefining K (can be decided from dendrogram).
-   Useful for small to medium datasets and deeper cluster analysis.

------------------------------------------------------------------------

📂 Dataset

-   Mall Customers Dataset
-   Features used:
    -   Annual Income (k$)
    -   Spending Score (1-100)

------------------------------------------------------------------------

📈 Results

🔹 K-Means Clustering

-   Number of clusters chosen = 5
-   Final groups:
    -   VIP Customers (High Income, High Spending)
    -   Inactive Customers (Low Income, Low Spending)
    -   Balanced Customers (Mid Income, Mid Spending)
    -   Saver Customers (Low Spending, Cost-conscious)
    -   Spender Customers (Impulsive spenders, not always rich)

📊 Visualization:
- Centroids shown with red stars.
- Clear separation of customer groups.

------------------------------------------------------------------------

🔹 Hierarchical Clustering

-   Dendrogram used to find optimal clusters = 5
-   Groups similar to K-Means but with slightly different boundaries.
-   Provides hierarchy of merges → useful for deeper insights.

📊 Visualization:
- Dendrogram shows customer merging process.
- Scatter plot with colored clusters.

------------------------------------------------------------------------

🧩 Comparison

  ------------------------------------------------------------------------
  Aspect                             K-Means        Hierarchical
  ---------------------------------- -------------- ----------------------
  Speed                              ✅ Fast        ❌ Slower

  Scalability                        ✅ Large       ❌ Small/medium only
                                     datasets       

  Deciding Clusters                  ❌ Must        ✅ Dendrogram helps
                                     predefine K    

  Interpretability                   Medium         ✅ Very High

  Best Use Case                      Customer       Deep analysis, smaller
                                     segmentation   data
                                     at scale       
  ------------------------------------------------------------------------

------------------------------------------------------------------------

💡 Business Insights

-   VIP Customers 💎 → Premium services, loyalty programs.
-   Inactive Customers 🚫 → Don’t invest too much in them.
-   Balanced Customers 🔄 → Steady base revenue, cross-sell services.
-   Saver Customers 💰 → Attract with coupons, avoid luxury upsells.
-   Spender Customers ⚡ → Promote limited-time offers, convert to VIP.

------------------------------------------------------------------------

⚙️ Technologies Used

-   Python 🐍
-   Scikit-learn 🤖
-   Scipy 📐
-   Pandas, NumPy 📊
-   Matplotlib 🎨

------------------------------------------------------------------------

👨‍💻 Author

SAIF ULLAH UMAR	
- 🎓 BS Artificial Intelligence Student @ New Tech University, Islamabad
- 💻 Aspiring Machine Learning Engineer
- 📂 GitHub: https://github.com/SaifUllahUmar0317
------------------------------------------------------------------------

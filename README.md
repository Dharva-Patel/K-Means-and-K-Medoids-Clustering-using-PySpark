# K-Means-and-K-Medoids-Clustering-using-PySpark

In this project, we performed sequential and parallel implementation of K-means and K-medoids Clustering algorithm. The main goal of our implementation is minimizing
runtime while maximizing accuracy in assigning cluster labels to data points. We implemented sequential algorithms using dataframes and parallel algorithms using PySpark RDD. 

**Work Done:**

  1.  Identifying problems in conventional data analysis methods.
  2.  Sequential and Parallel algorithm design and implementation of K-Means and K-Medoids Clustering algorithm.
  3.  Comparison of sequential and parallel clustering techniques using Silhouette Score along with run time comparison for both methods by varying the number of maximum iterations and keeping clusters constant.
  4.  Compariosn between performance of K-Means and K-Medoids clustering algorithm.
  
  We have used a country dataset from kaggle which contains: country, child_mort, health, imports, income, inflation, life_epec, total_fer, gdpp.

**Comparison of Sillhoute Scores:**

  |  | Sequential | Parallel |
  | :---:        |     :---:      |         :---: |
  | K-Means   |  0.6003679947620904   |  0.6003689044610714    |
  | K-Medoids     | 0.6492494728121732       | 0.6498575328920972      |
  
  (Detailed comparison is available in Final_Report)



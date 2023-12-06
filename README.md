# Customer_Segmenatation
**Introduction**

Customer Segmentation is the process of dividing the customers into groups based on common characteristics, so companies can market to  each group effectively and appropriately. 

In business to consumer marketing companies often segment customers according to demographics that include; 
Age, Location, Gender.

Segmentation allows marketers to better tailor their marketing efforts to various audience subsets. Those efforts can relate to both communication and product development. It helps in;
1.Focus on most profitable customers
2.Identify ways to improve products or service opportunities.
3.Establish better customer relationships.

**Methods and Modules**

The modules used in the project are as follows;

NumPy: - It is an open source package which helps in performing mathematical and logical operations. It stands for numerical python.

Pandas: - It is a python library which is used for data manipulation and analysis. It helps in reading different  formats of files.

Matplotlib: - It is a cross platform data visualization and graphical plotting library for python and it uses NumPy for various purpose.

Seaborn: - It is also a data visualization library based on matplotlib, it provides attractive and informative statistical graphics. It works well with pandas.

Sklearn: - It is the most useful library for machine learning in python. It helps in classification, Regression, clustering and dimensionality reduction.

**Discussion**

Customer segmentation  has been trending topic for many industries as it helps in making profitable decision for the company. Many firms had started using this method but the algorithm used (GMM, DBSCAN etc.) are less accurate which can cause problem. 

We have used KMeans clustering algorithm along with WCSS which is a better approach as it tells us the appropriate number of clusters according the data given. KMeans being one of the newest algorithms, has a comparatively better accuracy and a lower time complexity.

**Result**

We obtained results in two stages;

We used WCSS (Within cluster sum of squares) formula in order to find optimal number of clusters according the our data. The result came out to be 5 clusters. 

After getting the optimal number of clusters, we used unsupervised KMeans Clustering algorithm in order to perform Customer Segmentation. As a result, we got the appropriate clusters.

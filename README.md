CUSTOMER SEGMENTATION (Using Unsupervised Machine Learning in Python)

PROJECT OVERVIEW

This project focuses on segmenting customers based on their characteristics, behaviors, and needs using unsupervised machine learning techniques. Customer segmentation helps companies better understand their customers, enabling targeted marketing strategies, product development, and service improvement. The process involves data preprocessing, visualization, clustering, and model evaluation using Python.

DATASET

The dataset contains customer information such as:

Marital Status
Income
Number of items purchased
Types of items purchased
And other demographic and behavioral features.
Shape of the Dataset
Rows: 2240
Columns: 25

LIBRARIES USED

The following Python libraries are used in this project:

Pandas: For data manipulation and analysis.
Numpy: For numerical computations.
Matplotlib / Seaborn: For data visualization.
Sklearn: For machine learning, including preprocessing and clustering.

PROJECT WORKFLOW

1. Data Preprocessing
   
   Null Values Handling: We identified null values in the Income column and dropped the rows containing them since they were minimal.
   Unique Values: We identified columns with single values and removed them for relevance.
   Date Transformation: The Dt_Customer column was split into day, month, and year columns for better feature engineering.

2. Data Visualization
   
    Performed several visualizations such as count plots to understand the distribution of categorical variables like Marital_Status and Accepted.
    Visualized feature correlations using a heatmap.

3. Label Encoding

    Categorical variables were converted to numerical values using LabelEncoder to make them suitable for machine learning algorithms.
   
4. Standardization

    Standardization was applied using StandardScaler to scale the features, reducing the mean to 0 and standard deviation to 1.
  
5. Clustering

    T-distributed Stochastic Neighbor Embedding (T-SNE)
    T-SNE was used for dimensionality reduction and visualization of high-dimensional data.

K-Means Clustering

KMeans clustering was used to group the data into clusters. Using the elbow method, the optimal number of clusters was determined to be 5.
The clusters were visualized using a scatterplot.


Output:

![image](https://github.com/user-attachments/assets/d9c1c10d-e5a6-4a6e-9cd2-b118e9c47038)

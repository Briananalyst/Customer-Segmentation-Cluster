Customer Personality Analysis

This project focuses on Customer Personality Analysis using unsupervised machine learning techniques to better understand customer segments. By leveraging clustering algorithms, businesses can identify distinct customer groups, enabling targeted marketing and product customization. The data used for this analysis was sourced from Kaggle.

Overview

The goal of this project was to segment customers into clusters based on their purchasing behavior and demographics. This segmentation allows businesses to optimize their marketing strategies, for example, by identifying customer groups most likely to buy a new product and focusing marketing efforts on those segments.

Process

1. Data Acquisition and Cleaning
Source: The dataset was sourced from Kaggle.
Cleaning: Removed null values, handled outliers, and formatted categorical variables for analysis.
2. Exploratory Data Analysis (EDA)
Conducted detailed visualization and analysis of features such as customer spending, demographics, and purchase behavior.
Insights from EDA helped to identify patterns and correlations within the data.
3. Feature Engineering
Created new features such as total spending and combined existing features to better represent customer behavior.
Prepared the dataset for clustering by selecting relevant features.
4. Data Preprocessing
Applied standard scaling to normalize data for consistency and to ensure clustering algorithms perform optimally.
5. Model Selection
Used multiple unsupervised learning models to determine the most effective clustering approach:

     KMeans Clustering: To create distinct customer groups based on spending and demographics.

     Principal Component Analysis (PCA): To reduce dimensionality and visualize clusters in 2D and 3D spaces.

     Agglomerative Clustering: To explore hierarchical relationships among customers.

6. Cluster Labeling and Interpretation
Analyzed cluster labels to identify unique customer segments.
Assigned meaningful labels based on cluster behavior and spending patterns.

Conclusion

The clustering analysis provided actionable insights into customer segments, enabling targeted marketing strategies. For instance:

High-spending customers were identified,this include people who are single or parents who have less than 3 kids,people with high income,people with postgraduate; suggesting they could be prioritized for premium product offerings.

Budget-conscious customers were grouped, this include people who are married and parents of more than 3 kids,people with low income,people with undergraduate.

By understanding customer segments, businesses can efficiently allocate resources and market new products to the most relevant audiences, driving sales and improving customer satisfaction.

Tools and Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Machine Learning Models: KMeans, PCA, Agglomerative Clustering

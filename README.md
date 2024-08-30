## Customer Segmentation using Clustering

## Overview
This notebook focuses on developing a clustering model to segment credit card users based on their purchasing behavior and payment patterns. The aim is to gain deeper insights into customer profiles and optimize banking services by tailoring them to specific user segments. The project employs the Elbow method to determine the optimal number of clusters and interprets each cluster to identify key characteristics and potential business strategies.

## Notebook Purpose:
In this notebook, you will:

### Data Collection:
- **Authenticate with Google Cloud** to access BigQuery.
- **Extract customer data** using SQL queries from a BigQuery dataset.
- **Save the extracted data** to a CSV file for further analysis.

### Data Preprocessing:
- **Load the saved CSV file** and preprocess the dataset by handling missing values and encoding categorical variables.
- **Normalize and scale** the data to ensure accurate clustering.

### Exploratory Data Analysis (EDA):
- **Conduct exploratory analysis** to understand the distribution and relationships between features like purchase frequency, balance, and payment patterns.
- **Visualize clusters** using techniques such as PCA (Principal Component Analysis) to reduce dimensionality and understand the data structure.

### Model Development:
- **Apply the Elbow method** to determine the optimal number of clusters.
- **Train a K-means clustering model** and evaluate the cluster centers to interpret user segments.
- **Analyze cluster characteristics** to gain insights into user behavior.

### Model Interpretation:
- **Interpret the clusters** based on user engagement, purchasing behavior, and payment patterns.
- **Identify potential business strategies** for each cluster, such as targeting high-value customers with premium services or improving engagement for low-activity users.

### Model Evaluation:
- **Evaluate the clustering model** by comparing the inertia and silhouette score.
- **Validate the effectiveness** of clustering by analyzing how well the model segments the user base.

### Conclusion:
- **Summarize the findings** by highlighting the key insights from each cluster.
- **Provide actionable recommendations** for marketing and service optimization based on cluster analysis.

## Tools and Libraries:
- **Pandas**: Used for data manipulation and analysis, particularly in handling structured data.
- **NumPy**: Utilized for numerical operations and array manipulations.
- **Scikit-learn**: Employed for implementing the clustering algorithms (K-means) and evaluating model performance.
- **Matplotlib & Seaborn**: Used for creating visualizations and plotting the results of the EDA and clustering models.
- **Elbow Method**: Applied for determining the optimal number of clusters.
- **Principal Component Analysis (PCA)**: Used for dimensionality reduction and visualizing the clustering results.
- **Google Cloud BigQuery**: Used for querying and extracting large datasets.
- **Jupyter Notebook**: Environment for interactive development, documentation, and testing.


For details and to view the notebook, check out [this Jupyter Notebook](P1G6_Set_1_hafidz_masruri.ipynb)

For inference, refer to [this Jupyter Notebook](P1G6_Set_1_hafidz_masruri_inference.ipynb)

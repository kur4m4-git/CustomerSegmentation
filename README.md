# CustomerSegmentation

## Project Overview
Customer segmentation is a vital technique used by businesses to group their customers based on similar characteristics, behaviors, or preferences. This project leverages machine learning algorithms to perform segmentation, enabling businesses to target their customers more effectively.

## Objective
The main objective of this project is to segment customers into distinct groups based on their:

- Annual income.
- Spending score.
- Demographic details like age and gender.

## Dataset
- Name: Mall Customer Dataset
- Source: Kaggle

## Features:
- CustomerID: Unique identifier for each customer.
- Gender: Customer gender (Male/Female).
- Age: Age of the customer.
- Annual Income (k$): Annual income in thousand dollars.
- Spending Score (1-100): Score assigned based on customer spending behavior and frequency.
- Size: 200 rows and 5 columns.

## Approach
1. Data Preprocessing
- Handled missing values (if any).
- Scaled numerical features for clustering.
- Encoded categorical variables, such as gender.
2. Exploratory Data Analysis (EDA)
- Visualized customer distribution based on age, gender, income, and spending score.
- Analyzed correlations between features.
3. Clustering
- Determined the optimal number of clusters using:
- Elbow Method.
- Silhouette Score.
- Applied clustering algorithms: K-Means Clustering to group customers into meaningful clusters.
- Visualized clusters using scatter plots for better interpretation.
## Technologies Used
- Programming Language: Python

### Libraries:
- pandas - Data manipulation.
- numpy - Numerical computations.
- matplotlib, seaborn - Visualization.
- scikit-learn - Machine learning algorithms.

## Results
Customers were segmented into 4 clusters. Each cluster exhibited distinct patterns:

- Cluster 1: High income, high spending customers.
- Cluster 2: Low income, low spending customers.
- Cluster 3: Low income, high spending.
- Cluster 4: High income, low spending.

### Insights:
- Businesses can focus marketing efforts on high-value clusters.
- Identify potential areas for customer engagement and loyalty programs




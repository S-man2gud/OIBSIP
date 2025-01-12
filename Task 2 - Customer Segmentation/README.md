# Customer Segmentation Analysis

This project focuses on identifying distinct customer segments using unsupervised machine learning techniques. The analysis enables businesses to better understand their customers' behaviors, tailor marketing strategies, and optimize customer retention.

## Project Overview
Customer segmentation is a powerful tool that divides customers into groups with similar characteristics or behaviors. This project employs clustering techniques, such as K-Means, to segment customers based on their purchasing behavior, demographics, and engagement metrics.

The insights derived can help businesses:

- Identify high-value customers.
- Design targeted marketing campaigns.
- Improve product recommendations.
- Enhance customer satisfaction and loyalty.

## Dataset Description
The dataset contains 2,205 customer records with the following features:

- Demographics: Income, Age, Household Composition (Kids, Teens).
- Engagement Metrics: Recency of last purchase, number of web visits, catalog purchases, and store visits.
- Spending Behavior: Total spending across categories (e.g., wine, meat, fruits).

## Methodology
1. Data Preparation:
- Cleaning and selecting relevant features.
- Standardizing data for clustering.

2. Cluster Analysis:
- Determined the optimal number of clusters using the Elbow Method.
- Performed clustering using K-Means.

3. Visualization:
- Reduced dimensions using PCA for a 2D representation.
- Visualized clusters to identify distinct customer segments.

4. Insights and Recommendations:
- Analyzed cluster characteristics.
- Proposed actionable strategies tailored to each segment.

## Key Findings
1. Cluster Characteristics:
- High-Income, High-Spending Customers: Prefer luxury items.
- Budget-Conscious Customers: Respond to promotions and discounts.
- Family-Oriented Customers: Spend more on essentials and family needs.
- Inactive Customers: Low engagement and need reactivation strategies.

2. Optimal Clusters Identified: 4 distinct customer groups.

3. Actionable Recommendations:
- Implement loyalty programs, family bundles, and reactivation campaigns.
- Tailor digital marketing strategies for online-savvy customers.

## Technologies Used
- Programming Language: Python
- Libraries:
  - pandas and numpy for data manipulation.
  - scikit-learn for clustering and PCA.
  - matplotlib and seaborn for data visualization.

## Usage Instructions
### Prerequisites
- Install Python 3.8 or later.
- Install required libraries using pip:

pip install pandas numpy scikit-learn matplotlib seaborn

### Steps to Run the Project
1. Clone this repository:
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation

2. Add the dataset to the project directory (ifood_df.csv).

3. Run the Jupyter notebook or Python script for analysis:

4. python segmentation_analysis.py
5. View visualizations and results.

## Next Steps
- Advanced Clustering: Explore other clustering methods like DBSCAN or hierarchical clustering.
- Feature Engineering: Add new features to improve segmentation.
- Automated Reports: Create dashboards for real-time segmentation analysis.

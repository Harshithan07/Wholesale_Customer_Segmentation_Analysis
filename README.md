# Wholesale_Customer_Segmentation_Analysis

Wholesale Customer Segmentation – Clustering Analysis & Strategic Recommendations
ABOUT THE PROJECT:
This project involved performing clustering analysis on the Wholesale Customer Dataset using R to extract meaningful client segments and derive data-driven business recommendations. The analysis used both hierarchical and K-means clustering techniques to identify behavioral clusters among clients based on their spending across product categories. As the individual analyst, I conducted the technical modeling, evaluated optimal k using silhouette scores and SSE curves, and developed strategic recommendations based on segment insights.

USE CASE EXPLANATION:
Wholesale businesses often lack granular visibility into customer segments, which limits their ability to personalize offers and forecast demand accurately. This project tackles that issue by applying unsupervised learning to segment clients, enabling targeted marketing, supply chain optimization, and personalized service design. The insights can be used by wholesale providers, FMCG distributors, or any B2B company to better serve diverse clients like hotels, restaurants, or retailers.

HOW IT IS BUILT AND FULL WORKING:

Data Processing and Normalization:

Used R to clean and normalize six numerical spending features (Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicatessen).

Created distance matrices and applied both hierarchical clustering (ward.D) and K-means.

Model Evaluation:

Used SSE (elbow method) and silhouette scores to assess cluster quality.

K=3 was selected as the best configuration due to high silhouette score (0.44) and evenly distributed clusters.

Cluster Interpretation:

Cluster 1: Largest cluster (271 clients); low volume, high frequency; primarily Horeca (cafés, small restaurants).

Cluster 2: High fresh & frozen spending; represents large Horeca clients (hotels, fine dining).

Cluster 3: Mostly retail clients (91.4%); high spending on groceries and detergents — likely supermarkets and convenience stores.

Advanced Segmenting:

Ran separate clustering on Horeca and Retail segments to fine-tune targeting strategies.

Identified four subtypes within each segment (e.g., small cafés, large restaurants, small retailers, large supermarkets).

Correlation Insights:

Found strong correlation between Grocery and Detergents_Paper, suggesting potential for bundling promotions.

OUTPUT AND RESULTS OR BENCHMARKS:

Segmented 440 customers into 3 actionable clusters and derived targeted strategies.

Produced detailed regional breakdowns to support geo-targeted marketing and cold chain logistics planning.

Delivered key findings like:

37% of total spending came from Cluster 1

Grocery–Detergent correlation supports bundling

Cluster-specific needs (e.g., long-term contracts for Horeca, loyalty programs for Retail)

SKILLS, TOOLS:
R, K-Means Clustering, Hierarchical Clustering, ggplot2, dplyr, silhouette analysis, SSE evaluation, data normalization, market segmentation, cluster evaluation, correlation heatmaps

KEYWORDS:
Customer segmentation, K-means, unsupervised learning, hierarchical clustering, customer analytics, Horeca vs Retail, wholesale analytics, cluster interpretation, marketing strategy, cold chain logistics, correlation matrix, B2B personalization

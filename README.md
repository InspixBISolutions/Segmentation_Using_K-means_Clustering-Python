# Segmentation_Using_K-means_Clustering-Python
Segmentation with K-Means Clustering | Inspix BI Solutions

📊 Project Overview

This project demonstrates how Inspix BI Solutions uses unsupervised learning techniques to help universities and non-profit organizations optimize their donor engagement strategies. Using K-Means Clustering, we segmented alumni based on their donation patterns and demographic attributes, enabling data-driven fundraising and marketing campaigns.

🏫 Business Context

University advancement teams often struggle to understand which segments of their alumni are most likely to give, and how to best engage them. By applying clustering techniques, we uncover natural groupings within the donor base and generate actionable personas to drive personalized outreach.

📂 Dataset Description

The dataset represents anonymized records of university alumni with the following types of features:

Demographics: Gender, Province, Faculty of Graduation

Engagement: Relationship Type, Years Since Graduation

Giving Behavior: Lifetime Giving Amount, Annual Giving

Data was sourced from an Excel file and underwent several preprocessing steps to ensure quality.

🎯 Project Objectives

Clean and preprocess alumni donation data.

Encode categorical variables using ordinal encoding.

Apply K-Means Clustering to identify meaningful donor segments.

Visualize clusters and interpret segment characteristics.

Deliver insights to help advancement teams tailor their campaigns.

🧰 Tools & Technologies

Programming Language: Python 3

Libraries:

pandas (data manipulation)

numpy (numerical operations)

scikit-learn (K-Means, preprocessing)

matplotlib & seaborn (visualization)

🔍 Project Steps

1️⃣ Data Loading & Cleaning

Load Excel dataset using pandas.

Remove records with zero lifetime giving.

Drop irrelevant columns (e.g., titles).

2️⃣ Data Preprocessing

Encode categorical features: Gender, Province, Faculty, Relationship Type.

Handle missing or inconsistent data.

3️⃣ K-Means Clustering

Scale/normalize features if needed.

Use the Elbow Method to determine optimal number of clusters.

Fit K-Means and assign cluster labels.

4️⃣ Cluster Interpretation

Profile each cluster based on key features.

Visualize clusters using pair plots and bar charts.

5️⃣ Business Insights

Identify high-value donor segments.

Recommend targeting strategies for each group.

✅ Key Outcomes

Segmented alumni into distinct donor personas.

Provided advancement teams with insights into giving behaviors.

Highlighted clusters with strong potential for targeted fundraising.

Demonstrated Inspix BI’s strength in unsupervised learning and customer segmentation.

⚙️ How to Run This Notebook

Clone the repository:

git clone <repo_url>

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Launch the notebook:

jupyter notebook KMeans_clustering.ipynb

Follow the notebook steps to explore the analysis and results.

Note: Ensure the Excel file is correctly linked or loaded in your environment.

💼 About Inspix BI Solutions

Inspix BI Solutions empowers educational institutions, non-profits, and enterprises to unlock powerful insights through data analytics. From segmentation to forecasting, we turn your raw data into actionable strategies.

📞 Contact us: inspixbisolutions@gmail.com

Know your audience — speak to them through data. 🧠💡


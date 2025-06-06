# Customer-Segmentation-for-E-commerce-Business

## 🔗 Project Resources

You can access all project files, datasets, and visuals here:
[Google Drive Folder](https://drive.google.com/drive/folders/1emi-JnnQXeoLEU-5ZzdNLhEHSHDNN0po?usp=sharing)


📌 Project Overview
This project applies unsupervised machine learning techniques to segment customers of an e-commerce platform based on behavioral data. By identifying distinct customer groups, businesses can implement more targeted marketing strategies, improve user experience, and drive sales more effectively.

📊 Objective
To perform Customer Segmentation using K-Means Clustering on a synthetic dataset of 1,000,000 customer records. The goal is to group customers based on their online behavior and value to the business.

🧾 Dataset
The dataset contains the following features:

Email
Address
Average Session Length
Time on App
Time on Website
Length of Membership
Yearly Amount Spent

Some missing values were introduced intentionally to simulate real-world data cleaning challenges.

🧹 Step-by-Step Workflow
1. Data Cleaning
Handled missing values (imputation)

Removed irrelevant columns (Email, Address)

Checked and resolved duplicates and outliers

2. Exploratory Data Analysis (EDA)
Plotted feature distributions

Analyzed correlations between features

Observed user engagement patterns across app and website usage

3. Feature Scaling
Applied StandardScaler to normalize features

4. K-Means Clustering
Used the Elbow Method to determine the optimal number of clusters

Applied K-Means to segment customers into 4 distinct clusters

5. Dimensionality Reduction
Used PCA (Principal Component Analysis) to visualize customer clusters in 2D

6. Cluster Profiling
Generated descriptive statistics for each cluster

Labeled clusters based on behavioral patterns (e.g., high spenders, frequent app users, etc.)

📈 Business Insights
Cluster 1: High spenders, prefer mobile app — ideal for premium membership promotions

Cluster 2: Low spenders, shorter session time — may benefit from onboarding support

Cluster 3: Average users, use both app and website — potential for cross-channel campaigns

Cluster 4: Long-time members, moderate spenders — target for loyalty programs

💡 Recommendations
Optimize app experience for Cluster 1 (high app usage)

Offer discounts or bundles to Cluster 2 to increase retention

Develop loyalty rewards for Cluster 4 to improve engagement

📦 Future Enhancements
Deploy this model via a Streamlit dashboard or Flask API

Integrate real-time segmentation into CRM systems

Test model on actual business data

📁 Files in this Project
customer_segmentation.csv – Cleaned and clustered data

eda_visuals/ – Histograms, pairplots, and correlation heatmaps

customer_segments_pca.png – PCA visualization of customer clusters

kmeans_model.pkl – Saved clustering model (optional)


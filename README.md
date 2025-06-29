# Customer Segmentation with Clustering

This project applies unsupervised learning techniques to segment customers from a real-world e-commerce dataset across 47 countries. It aims to derive actionable insights for marketing optimisation and customer engagement.

## 📊 Objective
Group customers into meaningful segments based on behavioural and transactional features to guide targeted marketing strategies.

## 🔧 Key Techniques Used
- Feature engineering (Recency, Frequency, CLV, Avg. Unit Cost, Age)
- Outlier detection (IQR method)
- Principal Component Analysis (PCA)
- K-Means and Hierarchical Clustering
- Dimensionality reduction (t-SNE)
- Silhouette score & Elbow method for optimal k
- Data visualisation (Boxplots, Dendrograms, Projections)

## 🧠 Insights
- Identified 5 interpretable customer clusters (e.g. Loyal High-Value, Infrequent High-Spender, Dormant)
- Found 2.9% high-value outlier customers worth retaining as a separate segment
- Visualised clear separation using t-SNE, with PCA confirming variance distribution

  ## 📎 Versions Compared

This repository includes two versions of the customer segmentation pipeline:

### 1. `Bhattacharya_Arunima_CAM_C101_Week_6_Mini_project.ipynb`
- Baseline approach using IQR-based filtering.
- 5 customer segments revealed through K-Means and t-SNE.
- Balanced trade-off between customer retention and clean segmentation.

### 2. `Aggressive_Outlier_Flagging_Bhattacharya_Arunima_CAM_C101_Week_6_Mini-project.ipynb`
- Tighter clustering by flagging customers as outliers if they exceeded 2+ statistical limits.
- Enabled focus on core customers by removing noise.
- Useful for targeting retention or marketing exclusion.

These complementary analyses showcase the impact of outlier treatment on clustering effectiveness.

## 📁 Files
- `Bhattacharya_Arunima_CAM_C101_Week_6_Mini_project.ipynb`: Full analysis code and visualisations
- `Bhattacharya_Arunima_CAM_C101_W6_Mini-project.pdf`: Summary report with results and recommendations
- `Aggressive_Outlier_Flagging_Bhattacharya_Arunima_CAM_C101_Week_6_Mini-project.ipynb`: Revisit the same clustering task with more aggressive outlier detection.
## 🛠️ Libraries
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`: PCA, KMeans, StandardScaler, IsolationForest
- `scipy`, `tsne`, `warnings`

## 📌 Key Takeaways
This project demonstrates:
- Practical use of unsupervised ML in business settings
- Importance of robust feature engineering
- Model interpretability for business decisions

---

📬 For queries or collaborations, connect on [LinkedIn](https://www.linkedin.com/in/arunima-bhattacharya-researcher-phd/)

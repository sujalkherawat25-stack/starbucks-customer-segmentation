📊 Starbucks Customer Segmentation — Machine Learning (K-Means + PCA + t-SNE)

This project performs customer segmentation using the Starbucks Starbucks Rewards Dataset from Kaggle.

📂 Dataset Files Used
File	Description
profile.csv	Customer demographic data
transcript.csv	Transactions + offer events
portfolio.csv	Offer metadata
🔥 Project Highlights

✔ Processed 300k+ event records
✔ Engineered RFM features (Recency, Frequency, Monetary)
✔ Extracted offer behavior: receive/view/complete
✔ Applied PCA to reduce dimensionality
✔ Determined optimal clusters using:

Elbow Method (SSE)

Silhouette Score
✔ Applied K-Means clustering
✔ Visualized segments with t-SNE

🧠 Machine Learning Workflow

Data Cleaning + EDA

Feature Engineering (RFM + Offer Activity)

Standardization

PCA (90% Variance Retained)

K-Means Clustering

Model Evaluation (SSE + Silhouette)

t-SNE Cluster Visualization

Business Interpretation of Segments

📈 Visualizations

Add these screenshots:

![t-SNE Visualization](tsne_plot.png)
![Elbow Curve](elbow.png)
![Silhouette Scores](silhouette.png)

🚀 Tech Stack

Python, Pandas, NumPy

Scikit-Learn

Matplotlib, Seaborn

Google Colab

KaggleHub dataset loader

# CryptoClustering
This challenge involves analyzing cryptocurrency market data using K-Means clustering and Principal Component Analysis (PCA). The goal is to group cryptocurrencies based on their price change patterns and evaluate the impact of dimensionality reduction on clustering results.

Files
The csv file used-crypto_market_data.csv can be found in the resources folder.
The Jupyter Notebook-Crypto_Clustering.ipynb, contains all Python scripts for preprocessing, clustering, and visualization.

Technologies Used
-Python
-Pandas (Data handling)
-NumPy (Numerical operations)
-scikit-learn (K-Means clustering, PCA, StandardScaler)
-hvPlot (Interactive data visualization)
-Matplotlib (Elbow method visualization)

Key Findings
	•	K-Means clustering successfully groups cryptocurrencies based on price changes.
	•	PCA reduces the dataset dimensions while retaining most information, making clustering more efficient.
	•	Clusters may slightly shift when using PCA, highlighting the trade-off between dimensionality reduction and cluster interpretability.
	•	The Elbow Method helps determine the optimal number of clusters before and after PCA.

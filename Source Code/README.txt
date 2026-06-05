Retail Store Customer Clustering
Author: Aayushi Shah
Email: ajs.281004@gmail.com

Description:
This project applies K-Means clustering and PCA on the Mall_Customers dataset (Kaggle) to segment customers.

Folder contents:
- report/: Report.pdf (final PDF report)
- source_code/notebooks/: Jupyter Notebook(s) used (customer_segmentation.ipynb)
- outputs/models/: saved model files (kmeans_model.joblib, scaler.joblib, pca.joblib)
- dataset/: Mall_Customers.csv (original dataset)
- outputs/: resulting csvs and figures (mall_customers_with_clusters.csv, cluster_centroids.csv, figures/)
- requirements.txt: Python libraries required

Dataset Link:
https://www.kaggle.com/datasets/shwetabh123/mall-customers

How to run:
1. Install requirements: pip install -r requirements.txt
2. Open notebooks in Jupyter/Colab and run cells in order.
3. Or run scripts/run_clustering.py if included.

Notes:
- All file paths in notebooks are relative to the top-level folder.
- If using Colab, upload the dataset or mount Google Drive before running.

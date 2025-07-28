**Credit Card Customer Segmentation**
This project performs unsupervised clustering on credit card customer data to segment customers based on their spending behavior and financial attributes. Using PCA (Principal Component Analysis) for dimensionality reduction and K-Means clustering, the project identifies distinct customer groups that can help businesses in targeted marketing and customer relationship management.

**Key Features
Data preprocessing (missing values, scaling, feature selection)

Dimensionality reduction using PCA

K-Means clustering to identify customer segments

Visualization of clusters in 2D PCA space

Histogram plots for each feature across clusters

Eigen decomposition to determine the optimal number of principal components

Technologies Used
Python (NumPy, Pandas, Matplotlib, Seaborn)

Scikit-learn (PCA, KMeans)

Google Colab for execution

**Project Structure
bash
Copy
Edit
assets/Clustering/
│── Credit_Card_Customer_Segmentation.ipynb  # Main notebook
│── CreditCardData.csv                       # Dataset
│── plots/                                   # Cluster histograms and PCA plots

**How to Run
Open the notebook in Google Colab.

Clone the repository and set working directory.

Run all cells to preprocess, cluster, and visualize results.

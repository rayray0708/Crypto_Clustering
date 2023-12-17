![Illustration of Cryptocurrencies](https://m.foolcdn.com/media/dubs/images/original_imageshttpsg.foolcdn.comeditorialimag.width-880_1RsBqNB.jpg)
# Crypto_Clustering
## Description
In this project, I’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Usage
Please navigate to the "(copy)Crypto_Clustering_starter_code.ipynb" to see my code for the project.

To view the raw CSV file, please navigate to the "Resources" and select "crypto_market_data.csv".

## Installations

The following dependencies should be downloaded in order to run the code and display the graphs:\
-Pandas: (1) pip install pandas, (2) import pandas as pd\
-holoviews:  (1) pip install holoviews hvplot, (2) import holoviews as hv\
-hvPlot: import hvplot.pandas\
-warnings (optional): import warnings\
-KMeans: (1) pip install scikit-learn, (2) from sklearn.cluster import KMeans\
-PCA: from sklearn.decomposition import PCA\
-StandardScaler: from sklearn.preprocessing import StandardScaler

Notice that these were the libraries specifically used:
1) Pandas
2) HoloViews
3) Scikit-learn

### Cluster Cryptocurrencies with K-means Using the Original Data
![Clusters using K-means](<Screenshot 2023-12-17 at 9.14.52 pm.png>)

Using K-means algorithm, 4 clusters were created using the original data. This graph is displayed for comparison purposes with the below graph that was created using the Principal Component Analysis.

![Alt text](<Screenshot 2023-12-17 at 9.22.50 pm.png>)

Using fewer features, as displayed in the PCA plot, data points in a cluster (especially cluster 0 and 2) are more tightly grouped together. Using K-Means, data points are widely spread out and the clusters are not clearly separated (i.e., there's more overlap between clusters 0, 2 and 3 in the original data). 

## Credits
Special thanks to the following individuals for their contribution to the project:

-BCS tutors
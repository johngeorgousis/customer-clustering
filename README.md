# Customer Segments

The goal of this project was to identify potential customers for a global services company (Arvato). This was done by clustering the general population demographics (of Germany) into segments, mapping a customer dataset onto those segments, and then analysing the two cluster distributions to see where the strongest customer base for the company is. The following steps were taken:

- Pre-processed the general population data (missing value analysis, imputation, feature engineering)
-Used Seaborn for data visualisation to guide my decisions
- Created a cleaning function to repeat the cleaning tasks on the customer dataset
- Used Principal Component Analysis for dimensionality reduction
- Interpreted the most important principal components
- Used K-Means clustering to cluster the general population demographics dataset
- Mapped the customer dataset onto the demographics clusters
- Analysed over- and under-represented clusters to identify key latent features of customers
- Made a recommendation to the company

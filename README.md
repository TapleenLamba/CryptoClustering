# CryptoClustering

Project Overview:

This project is designed to forecast the impact of 24-hour or 7-day price changes on cryptocurrencies. Through a comprehensive analysis, it was determined that the optimal value for k remained consistent whether utilizing the original scaled data or the Principal Component Analysis (PCA) data. Notably, while the optimal k-value exhibited similarity, the K-Means clusters varied between the two datasets. Noteworthy differences include the observation that fewer features result in tighter clusters with reduced inertia, manifesting as a steeper curve.

Processes and Technologies:

The core of this project revolves around Python programming and employs unsupervised learning techniques to predict outcomes and visualize results. The initial step involved leveraging the StandardScaler() module from scikit-learn to standardize the data sourced from the CSV file. Subsequently, the K-means model was implemented to cluster cryptocurrencies based on the original scaled dataframe. Following this, Principal Component Analysis (PCA) was applied to condense the feature set to three principal components, allowing for a more concise representation of the data. The determination of the optimal k-value was then performed using the PCA data.

Despite the consistent identification of the optimal k-value (set at 4) for both the original scaled data and the PCA data, it is essential to note that the resulting K-Means clusters exhibited variance, emphasizing the impact of feature reduction on cluster tightness and inertia. This README file serves as a guide to the project's methodology and the technologies utilized, providing users with a comprehensive understanding of the processes involved.

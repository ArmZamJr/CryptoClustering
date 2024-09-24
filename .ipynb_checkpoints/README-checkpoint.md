# CryptoClustering
Module 11 Challenge
# StandardScaler
## 11-Unsupervised-Learning\2\Activities\04-Ever-Preprocessing\Solved\.ipyb_checkpoints\cc-preprocessing_solution-checkpoint.ipynb
I had issues with the k inertia but turns out the answer depends on which version of Python you are using.  May some notes on this would have helped so I would not of had spent hours trying to decifer my answer.

# Add a new column to the DataFrame with the predicted clusters
market_data_df["class"] = model.labels_
## 11-Unsupervised-Learning>2>Activities>07_Segmenting_Customers>Solved>cc_segmenting_customers_solution.ipynb
        labels = k_model.labels_
# Create a PCA model instance and set `n_components=3`.
pca = PCA(n_components=3)
### Determine the Weights of Each Feature on each Principal Component
ask-314863 
TA Andrew
Metin Akyol - Instructor 
all helped me understand the weights.
# Create a copy of the scaled PCA DataFrame
df_market_data_pca_predictions = df_market_data_pca.copy()

# Add a new column to the copy of the PCA DataFrame with the predicted clusters
df_market_data_pca_predictions["crypto_cluster"] = crypto_clusters_pca

# Display the copy of the scaled PCA DataFrame
df_market_data_pca_predictions.head()




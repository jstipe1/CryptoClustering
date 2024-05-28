# CryptoClustering - Module_11_Challenge

__Purpose__: In this Challenge we apply our understanding of the K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies according to their price fluctuations across various timeframes. 

  __Step 1__: Scale the data utilizing the StandardScaler()  
  __Step 2__: Use the elbow method on the scaled data to find the best value for K  
  __Step 3__: Initialize, fit, and predict based on the K-means model, then plot the results  
  __Step 4__: Using the scaled data set perform a PCA and reduce the features to three principal components  
  __Step 5__: Use the elbow method on the PCA data to find the best value for K  
  __Step 6__: Initialize, fit, and predict based on the K-means model on the PCA data, then plot the results  
  __Step 7__: Determine the Weights of Each Feature on Each Principal Component

__Intalls__: A number of installations are needed (and provided) to run the code necessary to complete this project  
  
  import pandas as pd  
  from sklearn.cluster import KMeans  
  from sklearn.decomposition import PCA  
  from sklearn.preprocessing import StandardScaler

[Python Documentation] (https://docs.python.org/)  
[Jupyter Notebook Documentation] (https://jupyter-notebook.readthedocs.io/)  
[sklearn Documentation]  (https://scikit-learn.org/0.21/documentation.html)



__Resources__:
[README.md formatting] (https://medium.com/analytics-vidhya/writing-github-readme-e593f278a796)  


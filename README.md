# kmeansCluster
kMeans example for final project
finalProjectCluster.Rmd is the R markdown template for the final unsupervised learning project.  Notice that a data frame 'fraud_ok' was set up; this contains only the transactions that have been investigated, frauds or ok.    The idea is to cluster using this data frame,and then use the characteristics of the fraud cluster to find transactions in the balance of the entire data set (Insp='unkn') to locate possible fraudulent transactions.   Kmeans requres that the input parameters be numeric, not categorical, since distances are computed.  Try different distance metrics?

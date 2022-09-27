K-Means is simple to implement but we need to specify number of clusters.
DBSCAN does not require number of clusters but it not suitable for large number of data.
Gaussian Mixture uses EM method which can be used to fill the missing value and is a special case of K-Means.
BIRCH groups the dense datapoints into a singe data point, the clustering is done automatically. if needed we can apecify the values. threshold is the number of ponts whch are grouped inside a cluster, branching factor is the tree and its value specifies no of nodes.
MEANSHIFt requires only one value called bandwidth, which is used in RBF kernal to find the non linear line for the model

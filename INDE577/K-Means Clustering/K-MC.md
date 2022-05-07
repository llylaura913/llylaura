# K Means Clustering

k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.

## Tasks: 

1. exploring original state 

2. clustering

3. exploring training 

4. eploring testing 

### Datasets: 

'FEV.cvs'

x1 = np.c_[df["Age"]]

x2 = np.c_[df["Hgt"]]

y = np.c_[df["FEV"]]

X = np.column_stack((x1,x2))   



```python

```

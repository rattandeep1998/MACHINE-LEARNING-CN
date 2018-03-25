## UNSUPERVISED LEARNING ##


### SIL HONITTE technique to get value of K in KMEANS ###

S(i) = [b(i) - a(i)] / max(a(i),b(i))

### K MEDOIDS ###
1. Take k point randomly as medoids.
2. CLUSTERING - Cluster all the points and decide kon se cluster me jaayega woh point...on the basis of distance metric (euclidian, manhattan, etc).
3. MEDOID UPDATE - For every point in m clusters, taking that as medoid and seeing that distance metric improves or not, if distance metric improves then we will choose that point as medoid.
4. Repeat step 2 and 3


K Medoids -- Self implementation

### Hierarchial Clustering ###

AGGLOMERATIVE CLUSTERING -- code using sklearn

Dendogram - splitting in hierarchial clustering and seeing the tree.

### Mean Shift Clustering ###

### Things to be done : ###

* Agglomerative Clustering using sklearn code
* Sil honitte - link(mentioned below) and code to choose best value of K
* Mean Shift - sklearn implementation 

Data Sets used :  Random 2D data points(make_blobs) :+1: 

:smiley:
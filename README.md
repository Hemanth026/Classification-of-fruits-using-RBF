# Classification-of-fruits-using-RBF

The code classifies the fruits using the Radial basis method.The dataset folder "file" contains images of three kinds namely apple, banana, orange and folder containing mixed images of these three.The images should be classified into test and train folders which is to be used for testing and training respectively. These images are preprocessed into Grayscale and then the train set images are fed to clustering algorithms to find the clustering centers. The implementation is carried out by two different classification algorithms namely Kmeans and Agglomerative clustering ( Hierarchical clustering ). The centroids are obtained from both the algorithms. The model is trained separately with both the centroid sets. Then testing is performed with respect to both the sets and the output is recorded. The output varies with the nubmer of clusters formed.

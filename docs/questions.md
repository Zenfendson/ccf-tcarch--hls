# 比赛题目

## **初赛题目**

### 初级题

>1. FFT
>2. Sobel

### 中级题

1.Training of Random Forest Model  

  > Random forest is an ensemble learning method that consisting a multitude of decision trees at training time and outputting the mode of the classes (classification) or mean prediction (regression) of the trees.  
  [**Source code**](https://github.com/Xilinx/Vitis_Libraries/tree/master/data_analytics/L2/tests/classification/randomforest)

2.Training of SVM Model
  > SVM (Support Vector Machine) is a model to predict sample’s classification. The svm_train function that trains a batch of samples using support vector machine model and output a weight vector for classification.  
[**Source code**](https://github.com/Xilinx/Vitis_Libraries/tree/master/data_analytics/L2/tests/classification/svm)

3.Regular Expression Engine
  > The regex-VM aims at the work of converting unstructured texts, like log files, into structured ones  
[**Source code**](https://github.com/Xilinx/Vitis_Libraries/tree/master/data_analytics/L2/tests/text/reEngine)


### 高级题3个

- Minimum Spanning Tree  
  > A minimum spanning tree is a subset of the edges of a weighted graph that connects all the vertices together. without any cycles and with the minimum possible total weight.

- K-1 Coloring
  >The K-1 Coloring algorithm assigns a color to every node in the graph, trying to optimize for two objectives:  
  > - To make sure that every neighbor of a given node has a different color than the node itself. 
  > - To use as few colors as possible.

- Estimated Diameter
  >The diameter of a graph is the greatest distance between any pair of vertices. The estimated diameter problem tries to find a distance that is close to the graph diameter as much as possible.



## **决赛题目**

### 中级题3选一

- Training of Decision Tree Model
  >Decision Tree (Classification/Regression) is a model to predict sample’s classification or regression value.  
  >[Source code](https://github.com/Xilinx/Vitis_Libraries/tree/master/data_analytics/L2/tests/classification/decisiontree)

- Training of kMeans Model
  >Fits new centers based native k-means using the existed samples and initial centers provide by user.  
  >[Source code](https://github.com/Xilinx/Vitis_Libraries/tree/master/data_analytics/L2/tests/clustering/kmeans)

- CSR/CSC Converter
  >The CSR/CSC converter function tries to convert a sparse matrix from the compressed sparse column (CSC) format to the compressed sparse row (CSR) format.  
  >[Source code](https://github.com/Xilinx/Vitis_Libraries/tree/master/graph/L2/tests/convert_csc_csr)

### 高级题3选一

- Random Walk
  >A random walk means that we start at one vertex, choose a neighbor to navigate to at random or based on a provided probability distribution, and then do the same from that vertex, keeping the resulting path in a list.

- Closeness Centrality
  >Calculate the closeness centrality of a given vertex. The closeness centrality of a vertex measures its average farness (inverse distance) to all other vertices. Vertices with a high closeness score have the shortest distances to all other vertices.

- Overlap Similarity
  >Calculate the overlap similarity of two vertices in a graph. The overlap similarity is computed using the following formula
  >![](./images/quentions_image1.png)



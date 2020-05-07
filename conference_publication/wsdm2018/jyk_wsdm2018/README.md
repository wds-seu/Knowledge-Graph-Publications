## Fast and Scalable Distributed Loopy Belief Propagation on Real-World Graphs

**author**:Saehan Jo,Jaemin Yoo,U Kang

**abstract**:Given graphs with millions or billions of vertices and edges, how can we efficiently make inferences based on partial knowledge? Loopy Belief Propagation (LBP) is a graph inference algorithm widely used in various applications including social network analysis, malware detection, recommendation, and image restoration. The algorithm calculates approximate marginal probabilities of vertices in a graph within a linear running time proportional to the number of edges. However, when it comes to real-world graphs with millions or billions of vertices and edges, this cost overwhelms the computing power of a single machine. Moreover, this kind of large-scale graphs does not fit into the memory of a single machine. Although several
distributed LBP methods have been proposed, previous works do not consider the properties of real-world graphs, especially the effect of power-law degree distribution on LBP. Therefore, our work focuses on developing a fast and scalable LBP for such large
real-world graphs on distributed environment.
In this paper, we propose DLBP, a Distributed Loopy Belief Propagation algorithm which efficiently computes LBP in a distributed manner across multiple machines. By setting the correct convergence criterion and carefully scheduling the computations, DLBP provides up to 10.7× speed up compared to standard distributed LBP. We show that DLBP demonstrates near-linear scalability with respect to the number of machines as well as the number of edges.

**keywords**:

**interpretation**:

**pdf**:[paper](https://jaeminyoo.github.io/resources/2018/WSDM/JoYK18.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
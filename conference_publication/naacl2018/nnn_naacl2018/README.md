# A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network
* **author**:  Dai Quoc Nguyen, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung
* **abstract**:  In this paper, we propose a novel embedding model, named ConvKB, for knowledge base completion. Our model ConvKB advances state-of-the-art models by employing a convolutional neural network, so that it can capture global relationships and transitional characteristics between entities and relations in knowledge bases. In ConvKB, each triple (head entity, relation, tail entity) is represented as a 3-column matrix where each column vector represents a triple element. This 3-column matrix is then fed to a convolution layer where multiple filters are operated on the matrix to generate different feature maps. These feature maps are then concatenated into a single feature vector representing the input triple. The feature vector is multiplied with a weight vector via a dot product to return a score. This score is then used to predict whether the triple is valid or not. Experiments show that ConvKB achieves better link prediction performance than previous state-of-the-art embedding models on two benchmark datasets WN18RR and FB15k-237. 
* **keywords**: 
* **interpretation**: 
* **pdf**: [paper](https://www.aclweb.org/anthology/N18-2053.pdf)
* **code**: [github](https://github.com/daiquocnguyen/ConvKB)
* **dataset**: WN18RR, FB15k-237
* **ppt/video**: 
* **curation**: Xiaoyu Shang

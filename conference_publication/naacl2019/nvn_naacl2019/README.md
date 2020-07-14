# A Capsule Network-based Embedding Model for Knowledge Graph Completion and Search Personalization
* **author**: Dai Quoc Nguyen, Thanh Vu, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung
* **abstract**: In this paper, we introduce an embedding model, named CapsE, exploring a capsule network to model relationship triples (subject, relation, object). Our CapsE represents each triple as a 3-column matrix where each column vector represents the embedding of an element in the triple. This 3-column matrix is then fed to a convolution layer where multiple filters are operated to generate different feature maps. These feature maps are reconstructed into corresponding capsules which are then routed to another capsule to produce a continuous vector. The length of this vector is used to measure the plausibility score of the triple. Our proposed CapsE obtains better performance than previous state-of-the-art embedding models for knowledge graph completion on two benchmark datasets WN18RR and FB15k-237, and outperforms strong search personalization baselines on SEARCH17. 
* **keywords**: 
* **interpretation**: 
* **pdf**: [paper](https://www.aclweb.org/anthology/N19-1226.pdf)
* **code**: [github](https://github.com/daiquocnguyen/CapsE)
* **dataset**: WN18RR, FB15k-237
* **ppt/video**: 
* **curation**: Xiaoyu Shang

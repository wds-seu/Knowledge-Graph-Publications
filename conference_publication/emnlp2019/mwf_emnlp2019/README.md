# Easy First Relation Extraction with Information Redundancy

- **author**: Shuai Ma, Gang Wang, Yansong Feng, Jinpeng Huai

- **abstract**: Many existing relation extraction (RE) models make decisions globally using integer linear programming (ILP). However, it is nontrivial to make use of integer linear programming as a blackbox solver for RE. Its cost of time and memory may become unacceptable with the increase of data scale, and redundant information needs to be encoded cautiously for ILP. In this paper, we propose an easy first approach for relation extraction with information redundancies, embedded in the results produced by local sentence level extractors, during which conflict decisions are resolved with domain and uniqueness constraints. Information redundancies are leveraged to support both easy first collective inference for easy decisions in the first stage and ILP for hard decisions in a subsequent stage. Experimental study shows that our approach improves the efficiency and accuracy of RE, and outperforms both ILP and neural network-based methods. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1398.pdf )

- **code**: 

- **dataset**: DB_me,DB_nn

- **ppt/video**:

- **curator**: Yawen Dai
# Learning to Hash for Efficient Search Over Incomplete Knowledge Graphs

* **author**:Meng Wang, Haomin Shen, Sen Wang, Lina Yao, Yinlin Jiang, Guilin Qi, Yang Chen:
* **abstract**:Knowledge graph (KG) embedding techniques represent entities and relations as low-dimensional, continuous vectors, and thus enables machine learning models to be easily adapted to KG completion and querying tasks. However, learned dense vectors are inefficient for large-scale similarity computations. Learning-to-hash is to learn compact binary codes from high-dimensional input data and provides a promising way to accelerate efficiency by measuring Hamming distance instead of Euclidean distance or dot-product. Unfortunately, most of learning-to-hash methods cannot be directly applied to KG structure encoding. In this paper, we introduce a novel framework for encoding incomplete KGs and graph queries in Hamming space. To preserve KG structure information from embeddings to hash codes and address the ill-posed gradient issue in optimization, we utilize a continuation method with convergence guarantees to jointly encode queries and KG entities with geometric operations. The hashed embedding of a query can be utilized to discover target answers from incomplete KGs whilst the efficiency has been greatly improved.We compared our model with state-of-the-art methods on real-world KGs. Experimental results show that our framework not only significantly speeds up the searching process, but also provides good results for unanswerable queries caused by incomplete information.
* **keywords**:binary codes,graph theory,learning (artificial intelligence),optimisation,query processing,vectors
* **interpretation**:
* **pdf**:[pdf](https://ieeexplore.ieee.org/abstract/document/8970688/authors)
* **code**:
* **dataset**:Bio,FB15K
* **ppt/video**:
* **curator**:Shuwei Yuan
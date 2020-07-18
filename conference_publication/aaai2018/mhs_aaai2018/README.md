# Data-Dependent Learning of Symmetric/Antisymmetric Relations for Knowledge Base Completion
* **author**: Hitoshi Manabe, Katsuhiko Hayashi, Masashi Shimbo
* **abstract**: Embedding-based methods for knowledge base completion (KBC) learn representations of entities and relations in a vector space, along with the scoring function to estimate the likelihood of relations between entities. The learnable class of scoring functions is designed to be expressive enough to cover a variety of real-world relations, but this expressive comes at the cost of an increased number of parameters. In particular, parameters in these methods are superfluous for relations that are either symmetric or antisymmetric. To mitigate this problem, we propose a new L1 regularizer for Complex Embeddings, which is one of the state-of-the-art embedding-based methods for KBC. This regularizer promotes symmetry or antisymmetry of the scoring function on a relation-by-relation basis, in accordance with the observed data. Our empirical evaluation shows that the proposed method outperforms the original Complex Embeddings and other baseline methods on the FB15k dataset.
* **keywords**: knowledge base completion
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16211/16597)
* **code**:
* **dataset**: WN18, FB15K
* **ppt/video**:
* **curation**: Jiong Zhang 

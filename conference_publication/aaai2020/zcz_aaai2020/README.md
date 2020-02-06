# Learning Hierarchy-Aware Knowledge Graph Embeddings for Link Prediction

* **author**:Zhanqiu Zhang, Jianyu Cai, Yongdong Zhang, Jie Wang
* **abstract**: Knowledge graph embedding, which aims to represent entities and relations as low dimensional vectors (or matrices, tensors, etc.), has been shown to be a powerful technique for predicting missing links in knowledge graphs. Existing knowledge graph embedding models mainly focus on modeling relation patterns such as symmetry/antisymmetry, inversion, and composition. However, many existing approaches fail to model semantic hierarchies, which are common in real-world applications. To address this challenge, we propose a novel knowledge graph embedding model---namely, Hierarchy-Aware Knowledge Graph Embedding (HAKE)---which maps entities into the polar coordinate system. HAKE is inspired by the fact that concentric circles in the polar coordinate system can naturally reflect the hierarchy. Specifically, the radial coordinate aims to model entities at different levels of the hierarchy, and entities with smaller radii are expected to be at higher levels; the angular coordinate aims to distinguish entities at the same level of the hierarchy, and these entities are expected to have roughly the same radii but different angles. Experiments demonstrate that HAKE can effectively model the semantic hierarchies in knowledge graphs, and significantly outperforms existing state-of-the-art methods on benchmark datasets for the link prediction task.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1911.09419)
* **code**:[github](https://github.com/MIRALab-USTC/KGE-HAKE)
* **dataset**:WN18RR,FB15k-237,YAGO3-10
* **ppt/video**:
* **curator**:Shuwei Yuan
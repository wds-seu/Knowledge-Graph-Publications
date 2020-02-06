# Knowledge Graph Alignment Network with Gated Multi-hop Neighborhood Aggregation

* **author**:Zequn Sun, Chengming Wang, Wei Hu, Muhao Chen, Jian Dai, Wei Zhang, Yuzhong Qu
* **abstract**: Graph neural networks (GNNs) have emerged as a powerful paradigm for embedding-based entity alignment due to their capability of identifying isomorphic subgraphs. However, in real knowledge graphs (KGs), the counterpart entities usually have non-isomorphic neighborhood structures, which easily causes GNNs to yield different representations for them. To tackle this problem, we propose a new KG alignment network, namely AliNet, aiming at mitigating the non-isomorphism of neighborhood structures in an end-to-end manner. As the direct neighbors of counterpart entities are usually dissimilar due to the schema heterogeneity, AliNet introduces distant neighbors to expand the overlap between their neighborhood structures. It employs an attention mechanism to highlight helpful distant neighbors and reduce noises. Then, it controls the aggregation of both direct and distant neighborhood information using a gating mechanism. We further propose a relation loss to refine entity representations. We perform thorough experiments with detailed ablation studies and analyses on five entity alignment datasets, demonstrating the effectiveness of AliNet.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1911.08936)
* **code**:[github](https://github.com/nju-websoft/AliNet)
* **dataset**: DBP15K,DWY100K
* **ppt/video**:
* **curator**:Shuwei Yuan
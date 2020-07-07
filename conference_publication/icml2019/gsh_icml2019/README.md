# Learning to Exploit Long-term Relational Dependencies in Knowledge Graphs
- **author**:  Lingbing Guo  Zequn Sun  Wei Hu
- **abstract**: We study the problem of knowledge graph (KG) embedding. A widely-established assumption to this problem is that similar entities are likely to have similar relational roles. However, existing related methods derive KG embeddings mainly based on triple-level learning, which lack the capability of capturing long-term relational dependencies of entities. Moreover, triple-level learning is insufficient for the propagation of semantic information among entities, especially for the case of cross-KG embedding. In this paper, we propose recurrent skipping networks (RSNs), which employ a skipping mechanism to bridge the gaps between entities. RSNs integrate recurrent neural networks (RNNs) with residual learning to efficiently capture the long-term relational dependencies within and between KGs. We design an end-to-end framework to support RSNs on different tasks. Our experimental results showed that RSNs outperformed state-of-the-art embedding based methods for entity alignment and achieved competitive performance for KG completion.
- **keywords**: KG embeddings  long-term relational dependencies
- **interpretation**:
- **pdf**: [paper](https://arxiv.org/pdf/1905.04914.pdf)
- **code**: 
- **dataset**: DBpedia and Wikidata
- **ppt/video**:
- **curator**: Jidong He

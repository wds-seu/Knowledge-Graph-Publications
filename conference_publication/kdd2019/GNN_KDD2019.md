# Estimating Node Importance in Knowledge Graphs Using Graph Neural Networks  
- **author**: Namyong Park, Andrey Kan, Xin Luna Dong, Tong Zhao, Christos Faloutsos
- **abstract**: How can we estimate the importance of nodes in a knowledge graph (KG)? A KG is a multi-relational graph that has proven valuable for many tasks including question answering and semantic search. In this paper, we present GENI, a method for tackling the problem of estimating node importance in KGs, which enables several downstream applications such as item recommendation and resource allocation. While a number of approaches have been developed to address this problem for general graphs, they do not fully utilize information available in KGs, or lack flexibility needed to model complex relationship between entities and their importance. To address these limitations, we explore supervised machine learning algorithms. In particular, building upon recent advancement of graph neural networks (GNNs), we develop GENI, a GNN-based method designed to deal with distinctive challenges involved with predicting node importance in KGs. Our method performs an aggregation of importance scores instead of aggregating node embeddings via predicate-aware attention mechanism and flexible centrality adjustment. In our evaluation of GENI and existing methods on predicting node importance in real-world KGs with different characteristics, GENI achieves 5–17% higher NDCG@100 than the state of the art.
- **keywords**: node importance estimation; knowledge graphs; graph neural networks; attention model
- **interpretation**:
- **pdf**: [paper](https://arxiv.org/pdf/1905.08865.pdf)
- **code**: 
- **dataset**: FB15K、MUSIC10K、TMDB5K、IMDB
- **ppt/video**:
- **curator**: Jidong He

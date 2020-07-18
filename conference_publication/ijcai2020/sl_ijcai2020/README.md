# Improving Attention Mechanism in Graph Neural Networks via Cardinality Preservation
* **author**: Shuo Zhang, Lei Xie
* **abstract**: Graph Neural Networks (GNNs) are powerful for the representation learning of graph-structured data. Most of the GNNs use a message-passing scheme, where the embedding of a node is iteratively updated by aggregating the information from its neighbors. To achieve a better expressive capability of node influences, attention mechanism has grown to be popular to assign trainable weights to the nodes in aggregation. Though the attention-based GNNs have achieved remarkable results in various tasks, a clear understanding of their discriminative capacities is missing. In this work, we present a theoretical analysis of the representational properties of the GNN that adopts the attention mechanism as an aggregator. Our analysis determines all cases when those attention-based GNNs can always fail to distinguish certain distinct structures. Those cases appear due to the ignorance of cardinality information in attention-based aggregation. To improve the performance of attention-based GNNs, we propose cardinality preserved attention (CPA) models that can be applied to any kind of attention mechanisms. Our experiments on node and graph classification confirm our theoretical analysis and show the competitive performance of our CPA models. The code is available online: https://github.com/zetayue/CPA.
* **keywords**: Graph Neural Network, attention 
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.ijcai.org/Proceedings/2020/194)
* **code**: [link](https://github.com/zetayue/CPA)
* **dataset**: REDDIT-BINARY, REDDITMULTI5K, MUTAG, PROTEINS, ENZYMES, NCI1
* **ppt/video**:
* **curation**: Jiong Zhang 
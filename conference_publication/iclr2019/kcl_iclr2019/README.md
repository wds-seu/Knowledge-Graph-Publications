# Rethinking Knowledge Graph Propagation for Zero-Shot Learning
* **author**：Michael Kampffmeyer, Yinbo Chen, Xiaodan Liang, Hao Wang, Yujia Zhang, Eric P. Xing
* **abstract**: Graph convolutional neural networks have recently shown great potential for the task of zero-shot learning. These models are highly sample efficient as related concepts in the graph structure share statistical strength allowing generalization to new classes when faced with a lack of data. However, we find that the extensive use of Laplacian smoothing at each layer in current approaches can easily dilute the knowledge from distant nodes and consequently decrease the performance in zero-shot learning. In order to still enjoy the benefit brought by the graph structure while preventing the dilution of knowledge from distant nodes, we propose a Dense Graph Propagation (DGP) module with carefully designed direct links among distant nodes. DGP allows us to exploit the hierarchical graph structure of the knowledge graph through additional connections. These connections are added based on a node's relationship to its ancestors and descendants. A weighting scheme is further used to weigh their contribution depending on the distance to the node. Combined with finetuning of the representations in a two-stage training approach our method outperforms state-of-the-art zero-shot learning approaches.
* **keywords**: Dense graph propagation, zero-shot learning
* **interpretation**: 
* **pdf**:  [link](https://openreview.net/pdf?id=rkgs0oAqFQ)
* **code**: 
* **dataset**: ImageNet 2012, Wikipedia
* **ppt/video**: 
* **curator**: Chang Liu

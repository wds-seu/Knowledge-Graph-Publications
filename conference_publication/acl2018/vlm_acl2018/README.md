# Probabilistic Embedding of Knowledge Graphs with Box Lattice Measures

* **author**：Luke Vilnis, Xiang Li, Shikhar Murty, Andrew McCallum
* **abstract**: Embedding methods which enforce a partial order or lattice structure over the concept space, such as Order Embeddings (OE), are a natural way to model transitive relational data (e.g. entailment graphs). However, OE learns a deterministic knowledge base, limiting expressiveness of queries and the ability to use uncertainty for both prediction and learning (e.g. learning from expectations). Probabilistic extensions of OE have provided the ability to somewhat calibrate these denotational probabilities while retaining the consistency and inductive bias of ordered models, but lack the ability to model the negative correlations found in real-world knowledge. In this work we show that a broad class of models that assign probability measures to OE can never capture negative correlation, which motivates our construction of a novel box lattice and accompanying probability measure to capture anti-correlation and even disjoint concepts, while still providing the benefits of probabilistic modeling, such as the ability to perform rich joint and conditional queries over arbitrary sets of concepts, and both learning from and predicting calibrated uncertainty. We show improvements over previous approaches in modeling the Flickr and WordNet entailment graphs, and investigate the power of the model.
* **keywords**: 
* **interpretation**: 
* **pdf**:  [link](https://www.aclweb.org/anthology/P18-1025.pdf)
* **code**: 
* **dataset**: WordNet
* **ppt/video**: 
* **curator**: Chang Liu

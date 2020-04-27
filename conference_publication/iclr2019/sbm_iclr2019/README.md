# Probabilistic Knowledge Graph Embeddings
* **author**：Farnood Salehi, Robert Bamler, Stephan Mandt
* **abstract**: We develop a probabilistic extension of state-of-the-art embedding models for link prediction in relational knowledge graphs. Knowledge graphs are collections of relational facts, where each fact states that a certain relation holds between two entities, such as people, places, or objects. We argue that knowledge graphs should be treated within a Bayesian framework because even large knowledge graphs typically contain only few facts per entity, leading effectively to a small data problem where parameter uncertainty matters. We introduce a probabilistic reinterpretation of the DistMult (Yang et al., 2015) and ComplEx (Trouillon et al., 2016) models and employ variational inference to estimate a lower bound on the marginal likelihood of the data. We find that the main benefit of the Bayesian approach is that it allows for efficient, gradient based optimization over hyperparameters, which would lead to divergences in a non-Bayesian treatment. Models with such learned hyperparameters improve over the state-of-the-art by a significant margin, as we demonstrate on several benchmarks. 
* **keywords**: knowledge graph, variational inference, probabilistic models, representation learning
* **interpretation**: 
* **pdf**:  [link](https://openreview.net/pdf?id=rJ4qXnCqFX)
* **code**: 
* **dataset**: f FB15K, WN18, FB15K-237, WN18RR 
* **ppt/video**: 
* **curator**: Chang Liu

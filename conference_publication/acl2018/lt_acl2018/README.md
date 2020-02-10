# Improving Entity Linking by Modeling Latent Relations between Mentions
* **author**：Phong Le, Ivan Titov
* **abstract**: Entity linking involves aligning textual mentions of named entities to their corresponding entries in a knowledge base. Entity linking systems often exploit relations between textual mentions in a document (e.g., coreference) to decide if the linking decisions are compatible. Unlike previous approaches, which relied on supervised systems or heuristics to predict these relations, we treat relations as latent variables in our neural entity-linking model. We induce the relations without any supervision while optimizing the entity-linking system in an end-to-end fashion. Our multi-relational model achieves the best reported scores on the standard benchmark (AIDA-CoNLL) and substantially outperforms its relation-agnostic version. Its training also converges much faster, suggesting that the injected structural bias helps to explain regularities in the training data.
* **keywords**: 
* **interpretation**: 
* **pdf**:  [link](https://www.aclweb.org/anthology/P18-1148.pdf)
* **code**: 
* **dataset**: AIDA-CoNLL
* **ppt/video**: 
* **curator**: Chang Liu

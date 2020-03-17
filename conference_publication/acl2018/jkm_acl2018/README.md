# Type-Sensitive Knowledge Base Inference Without Explicit Type Supervision
* **author**：Prachi Jain, Pankaj Kumar, Mausam, Soumen Chakrabarti
* **abstract**: State-of-the-art knowledge base completion (KBC) models predict a score for every known or unknown fact via a latent factorization over entity and relation embeddings. We observe that when they fail, they often make entity predictions that are incompatible with the type required by the relation. In response, we enhance each base factorization with two type-compatibility terms between entity-relation pairs, and combine the signals in a novel manner. Without explicit supervision from a type catalog, our proposed modification obtains up to 7% MRR gains over base models, and new state-of-the-art results on several datasets. Further analysis reveals that our models better represent the latent types of entities and their embeddings also predict supervised types better than the embeddings fitted by baseline models.
* **keywords**: 
* **interpretation**: 
* **pdf**:  [link](https://www.aclweb.org/anthology/P18-2013.pdf)
* **code**: 
* **dataset**: FB15K, FB15K-237, YAGO3-10
* **ppt/video**: 
* **curator**: Chang Liu

# Translating Embeddings for Knowledge Graph Completion with Relation Attention Mechanism
* **author**：Wei Qian, Cong Fu, Yu Zhu, Deng Cai, Xiaofei He
* **abstract**: Knowledge graph embedding is an essential problem in knowledge extraction. Recently, translation based embedding models (e.g., TransE) have received increasingly attentions. These methods try to interpret the relations among entities as translations from head entity to tail entity and achieve promising performance on knowledge graph completion. Previous researchers attempt to transform the entity embedding concerning the given relation for distinguishability. Also, they naturally think the relation-related transforming should reflect attention mechanism, which means it should focus on only a part of the attributes. However, we found previous methods are failed with creating attention mechanism, and the reason is that they ignore the hierarchical routine of human cognition. When predicting whether a relation holds between two entities, people first check the category of entities, then they focus on fined-grained relation-related attributes to make the decision. In other words, the attention should take effect on entities filtered by the right category. In this paper, we propose a novel knowledge graph embedding method named TransAt to learn the translation based embedding, relation-related categories of entities and relation-related attention simultaneously. Extensive experiments show that our approach outperforms state-of-the-art methods significantly on public datasets, and our method can learn the true attention varying among relations.
* **keywords**:Natural Language Processing: Knowledge Extraction, Natural Language Processing: Embeddings
* **interpretation**: 
* **pdf**:  [link](https://www.ijcai.org/Proceedings/2018/0596.pdf)
* **code**: 
* **dataset**: WN18, FB15k, WN11, FB13 
* **ppt/video**: 
* **curator**: Chang Liu

# TransMS: Knowledge Graph Embedding for Complex Relations by Multidirectional Semantics

- **author**:Shihui Yang, Jidong Tian, Honglun Zhang, Junchi Yan, Hao He, Yaohui Jin

- **abstract**: Knowledge graph embedding, which projects the symbolic relations and entities onto low-dimension continuous spaces, is essential to knowledge graph completion. Recently, translation-based embedding models (e.g. TransE) have aroused increasing attention for their simplicity and effectiveness. These models attempt to translate semantics from head entities to tail entities with the relations and infer richer facts outside the knowledge graph. In this paper, we propose a novel knowledge graph embedding method named TransMS, which translates and transmits multidirectional semantics: i) the semantics of head/tail entities and relations to tail/head entities with nonlinear functions and ii) the semantics from entities to relations with linear bias vectors. Our model has merely one additional parameter α than TransE for each triplet, which results in its better scalability in large-scale knowledge graph. Experiments show that TransMS achieves substantial improvements against state-of-the-art baselines, especially the Hit@10s of head entity prediction for N-1 relations and tail entity prediction for 1-N relations improved by about 27.1% and 24.8% on FB15K database respectively.

- **keywords**:Knowledge Representation and Reasoning: Knowledge Representation Languages

  Natural Language Processing: Natural Language Semantics

  Machine Learning: Knowledge-based Learning

  Natural Language Processing: Embeddings

- **interpretation**:待补充

- **pdf**: [pdf](https://www.ijcai.org/Proceedings/2019/0268.pdf)

- **code**:

- **dataset**:FB15K-237,WN18RR

- **ppt/video**:

- **curator**: Yawen Dai
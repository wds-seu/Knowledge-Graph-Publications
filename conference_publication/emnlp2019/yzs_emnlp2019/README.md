# Aligning Cross-Lingual Entities with Multi-Aspect Information

- **author**:Hsiu-Wei Yang,Yanyan Zou,Peng Shi,Wei Lu,Jimmy Lin,Xu Sun
- **abstract**: Multilingual knowledge graphs (KGs), such as YAGO and DBpedia, represent entities in different languages. The task of cross-lingual entity alignment is to match entities in a source language with their counterparts in target languages. In this work, we investigate embedding-based approaches to encode entities from multilingual KGs into the same vector space, where equivalent entities are close to each other. Specifically, we apply graph convolutional networks (GCNs) to combine multi-aspect information of entities, including topological connections, relations, and attributes of entities, to learn entity embeddings. To exploit the literal descriptions of entities expressed in different languages, we propose two uses of a pretrained multilingual BERT model to bridge cross-lingual gaps. We further propose two strategies to integrate GCN-based and BERT-based modules to boost performance. Extensive experiments on two benchmark datasets demonstrate that our method significantly outperforms existing systems. 
- **keywords**:
- **interpretation**:待补充
- **pdf**: [pdf](https://arxiv.org/pdf/1910.06575)
- **code**: [code](https://github.com/h324yang/HMAN)
- **dataset**: DBP15K,DBP100K 
- **ppt/video**:
- **curator**: Yawen Dai
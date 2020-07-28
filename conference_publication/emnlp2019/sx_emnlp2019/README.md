# Modeling Multi-mapping Relations for Precise Cross-lingual Entity Alignment

- **author**: Xiaofei Shi ,Yanghua Xiao 

- **abstract**: Entity alignment aims to find entities in different knowledge graphs (KGs) that refer to the same real-world object. An effective solution for cross-lingual entity alignment is crucial for many cross-lingual AI and NLP applications. Recently many embedding-based approaches were proposed for cross-lingual entity alignment. However, almost all of them are based on TransE or its variants, which have been demonstrated by many studies to be unsuitable for encoding multi-mapping relations such as 1-N, N-1 and N-N relations, thus these methods obtain low alignment precision. To solve this issue, we propose a new embedding-based framework. Through defining dot product-based functions over embeddings, our model can better capture the semantics of both 1-1 and multi-mapping relations. We calibrate embeddings of different KGs via a small set of pre-aligned seeds. We also propose a weighted negative sampling strategy to generate valuable negative samples during training and we regard prediction as a bidirectional problem in the end. Experimental results (especially with the metric *Hits@1*) on real-world multilingual datasets show that our approach significantly outperforms many other embedding-based approaches with state-of-the-art performance. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1075.pdf )

- **code**:

- **dataset**:  DBP15K

- **ppt/video**:

- **curator**: Yawen Dai

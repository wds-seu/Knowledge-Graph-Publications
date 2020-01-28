# Entity Alignment between Knowledge Graphs Using Attribute Embeddings 
- **author**: Bayu Distiawan Trisedya, Jianzhong Qi, Rui Zhang  
- **abstract**: The task of entity alignment between knowledge graphs aims to find entities in two knowledge graphs that represent the same real-world entity. Recently, embedding-based models are proposed for this task. Such models are built on top of a knowledge graph embedding model that learns entity embeddings to capture the semantic similarity between entities in the same knowledge graph. We propose to learn embeddings that can capture the similarity between entities in different knowledge graphs. Our proposed model helps align entities from different knowledge graphs, and hence enables the integration of multiple knowledge graphs. Our model exploits large numbers of attribute triples existing in the knowledge graphs and generates attribute character embeddings. The attribute character embedding shifts the entity embeddings from two knowledge graphs into the same space by computing the similarity between entities based on their attributes. We use a transitivity rule to further enrich the number of attributes of an entity to enhance the attribute character embedding. Experiments using real-world knowledge bases show that our proposed model achieves consistent improvements over the baseline models by over 50% in terms of hits@1 on the entity alignment task.
- **keywords**: Graph Embeddings; Entity Linking; Knowledge Graph
- **interpretation**: [OpenKG](https://mp.weixin.qq.com/s/Q-NlOwypscK8x2vooS2B8w)
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/3798/3676)
- **code**:
- **dataset**: DBP-LGD, DBP-GEO, DBP-YAGO (extracted from DBpedia, LinkedGeoData, Geonames and YAGO)
- **ppt/video**:
- **curator**: Xiaoyu Shang 

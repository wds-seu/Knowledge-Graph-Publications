# Graph Pattern Entity Ranking Model for Knowledge Graph Completion
* **author**: Takuma Ebisu, Ryutaro Ichise
* **abstract**: Knowledge graphs have been developed rapidly in recent years and shown their usefulness for many artificial intelligence tasks. However, knowledge graphs often have lots of missing facts. To solve this problem, many knowledge graph embedding models to populate knowledge graphs have been developed and have shown outstanding performance these days. However, knowledge graph embedding models are so called-black box. Hence, we actually does not know how information of a knowledge graph is processed and the models are hard to interpret. In this paper, we utilize graph patterns in a knowledge graph to overcome such problems. Our proposed model, graph pattern entity ranking Model (GRank), constructs an entity ranking system for each graph pattern and evaluate them using a measure for a ranking system. By doing so, we can find helpful graph patterns for predicting facts. Then we conduct the link prediction tasks on standard data sets to evaluate GRank. We show our approach outperforms other state-of-the-art approaches such as ComplEx and TorusE on standard metrics such as HITS@n and MRR. Moreover, This model is easily interpretable because output facts are described by graph patterns.
* **keywords**: 
* **interpretation**: 
* **pdf**: [paper]((https://www.aclweb.org/anthology/N19-1104.pdf))
* **code**: 
* **dataset**: WN18, WN18RR, FB15K, FB15K-237
* **ppt/video**: [video](https://vimeo.com/353483121)
* **curation**: Xiaoyu Shang

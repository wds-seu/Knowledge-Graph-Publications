# BERT-INT:A BERT-based Interaction Model For Knowledge Graph Alignment
* **author**: Xiaobin Tang, Jing Zhang, Bo Chen, Yang Yang, Hong Chen, Cuiping Li
* **abstract**: Knowledge graph alignment aims to link equivalent entities across different knowledge graphs. To utilize both the graph structures and the side information such as name, description and attributes, most of the works propagate the side information especially names through linked entities by graph neural networks. However, due to the heterogeneity of different knowledge graphs, the alignment accuracy will be suffered from aggregating different neighbors. This work presents an interaction model to only leverage the side information. Instead of aggregating neighbors, we compute the interactions between neighbors which can capture fine-grained matches of neighbors. Similarly, the interactions of attributes are also modeled. Experimental results show that our model significantly outperforms the best state-of-the-art methods by 1.9-9.7% in terms of HitRatio@1 on the dataset DBP15K.
* **keywords**: KG alignment
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.ijcai.org/Proceedings/2020/439)
* **code**: [link](https://github.com/kosugi11037/bert-int)
* **dataset**: DBP15K
* **ppt/video**:
* **curation**: Jiong Zhang 
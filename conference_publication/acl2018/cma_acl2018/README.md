# A Walk-based Model on Entity Graphs for Relation Extraction
* **author**：Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou
* **abstract**: We present a novel graph-based neural network model for relation extraction. Our model treats multiple pairs in a sentence simultaneously and considers interactions among them. All the entities in a sentence are placed as nodes in a fully-connected graph structure. The edges are represented with position-aware contexts around the entity pairs. In order to consider different relation paths between two entities, we construct up to l-length walks between each pair. The resulting walks are merged and iteratively used to update the edge representations into longer walks representations. We show that the model achieves performance comparable to the state-of-the-art systems on the ACE 2005 dataset without using any external tools.
* **keywords**: 
* **interpretation**: [link](https://blog.csdn.net/qq_37014750/article/details/83386852)
* **pdf**:  [link](https://www.aclweb.org/anthology/P18-2014.pdf)
* **code**: [link](https://github.com/automl/RoBO)
* **dataset**: ACE 2005
* **ppt/video**: 
* **curator**: Chang Liu

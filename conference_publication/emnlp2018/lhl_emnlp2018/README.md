## Differentiating Concepts and Instances for Knowledge Graph Embedding

**author**:Xin Lv, Lei Hou, Juanzi Li, Zhiyuan Liu

**abstract**:Concepts, which represent a group of different instances sharing common properties, are essential information in knowledge representation. Most conventional knowledge embedding methods encode both entities (concepts and instances) and relations as vectors in a low dimensional semantic space equally, ignoring the difference between concepts and instances. In this paper, we propose a novel knowledge graph embedding model named TransC by differentiating concepts and instances. Specifically, TransC encodes each concept in knowledge graph as a sphere and each instance as a vector in the same semantic space. We use the relative positions to model the relations between concepts and instances (i.e., instanceOf), and the relations between concepts and sub-concepts (i.e.,
subClassOf). We evaluate our model on both link prediction and triple classification tasks on the dataset based on YAGO. Experimental results show that TransC outperforms state-of-the-art methods, and captures the semantic transitivity for instanceOf
and subClassOf relation. Our codes and datasets can be obtained from https://github.com/davidlvxin/TransC.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1222.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
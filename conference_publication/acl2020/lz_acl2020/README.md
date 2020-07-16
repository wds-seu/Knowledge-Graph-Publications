#  Bipartite Flat-Graph Network for Nested Named Entity Recognition

* **author**: Ying Luo, Hai Zhao
* **abstract**:In this paper, we propose a novel bipartite flat-graph network (BiFlaG) for nested named entity recognition (NER), which contains two subgraph modules: a flat NER module for outermost entities and a graph module for all the entities located in inner layers. Bidirectional LSTM (BiLSTM) and graph convolutional network (GCN) are adopted to jointly learn flat entities and their inner dependencies. Different from previous models, which only consider the unidirectional delivery of information from innermost layers to outer ones (or outside-to-inside), our model effectively captures the bidirectional interaction between them. We first use the entities recognized by the flat NER module to construct an entity graph, which is fed to the next graph module. The richer representation learned from graph module carries the dependencies of inner entities and can be exploited to improve outermost entity predictions. Experimental results on three standard nested NER datasets demonstrate that our BiFlaG outperforms previous state-of-the-art models.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2005.00436)
* **code**:[github](https://github.com/cslydia/BiFlaGR)
* **dataset**: ACE2005,GENIA
* **ppt/video**:
* **curator**:Shuwei Yuan
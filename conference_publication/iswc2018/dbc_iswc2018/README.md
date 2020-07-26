# EARL: Joint Entity and Relation Linking for Question Answering over Knowledge Graphs
* **author**：Mohnish Dubey, Debayan Banerjee, Debanjan Chaudhuri, Jens Lehmann
* **abstract**: Many question answering systems over knowledge graphs rely on entity and relation linking components in order to connect the natural language input to the underlying knowledge graph. Traditionally, entity linking and relation linking have been performed either as dependent sequential tasks or as independent parallel tasks. In this paper, we propose a framework called EARL, which performs entity linking and relation linking as a joint task. EARL implements two different solution strategies for which we provide a comparative analysis in this paper: The first strategy is a formalisation of the joint entity and relation linking tasks as an instance of the Generalised Travelling Salesman Problem (GTSP). In order to be computationally feasible, we employ approximate GTSP solvers. The second strategy uses machine learning in order to exploit the connection density between nodes in the knowledge graph. It relies on three base features and re-ranking steps in order to predict entities and relations. We compare the strategies and evaluate them on a dataset with 5000 questions. Both strategies significantly outperform the current state-of-the-art approaches for entity and relation linking.
* **keywords**: Entity linking, Relation linking, GTSP, Question answering 
* **interpretation**: [link_1](https://blog.csdn.net/weixin_40871455/article/details/85052442)
* **pdf**:  [link](https://arxiv.org/pdf/1801.03825.pdf)
* **code**: [link](https://github.com/AskNowQA/EARL)
* **dataset**: LC-QuAD, QALD-7 
* **ppt/video**: 
* **curator**: Chang Liu

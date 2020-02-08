# Coordinated Reasoning for Cross-Lingual Knowledge Graph Alignment

* **author**: Kun Xu, Linfeng Song, Yansong Feng, Yan Song, Dong Yu
* **abstract**:Existing entity alignment methods mainly vary on the choices of encoding the knowledge graph, but they typically use the same decoding method, which independently chooses the local optimal match for each source entity. This decoding method may not only cause the "many-to-one" problem but also neglect the coordinated nature of this task, that is, each alignment decision may highly correlate to the other decisions. In this paper, we introduce two coordinated reasoning methods, i.e., the Easy-to-Hard decoding strategy and joint entity alignment algorithm. Specifically, the Easy-to-Hard strategy first retrieves the model-confident alignments from the predicted results and then incorporates them as additional knowledge to resolve the remaining model-uncertain alignments. To achieve this, we further propose an enhanced alignment model that is built on the current state-of-the-art baseline. In addition, to address the many-to-one problem, we propose to jointly predict entity alignments so that the one-to-one constraint can be naturally incorporated into the alignment prediction. Experimental results show that our model achieves the state-of-the-art performance and our reasoning methods can also significantly improve existing baselines.
* **keywords**:
* **interpretation**:
* **pdf**: [link](https://arxiv.org/pdf/2001.08728)
* **code**:
* **dataset**:DBP15K(ZH-EN),DBP15K(JA-EN),DBP15K(FR-EN)
* **ppt/video**:
* **curator**:Shuwei Yuan
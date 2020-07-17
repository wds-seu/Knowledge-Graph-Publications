# Relabel the Noise: Joint Extraction of Entities and Relations via Cooperative Multiagents

* **author**: Daoyuan Chen, Yaliang Li, Kai Lei, Ying Shen
* **abstract**:Distant supervision based methods for entity and relation extraction have received increasing popularity due to the fact that these methods require light human annotation efforts. In this paper, we consider the problem of \textit{shifted label distribution}, which is caused by the inconsistency between the noisy-labeled training set subject to external knowledge graph and the human-annotated test set, and exacerbated by the pipelined entity-then-relation extraction manner with noise propagation. We propose a joint extraction approach to address this problem by re-labeling noisy instances with a group of cooperative multiagents. To handle noisy instances in a fine-grained manner, each agent in the cooperative group evaluates the instance by calculating a continuous confidence score from its own perspective; To leverage the correlations between these two extraction tasks, a confidence consensus module is designed to gather the wisdom of all agents and re-distribute the noisy training set with confidence-scored labels. Further, the confidences are used to adjust the training losses of extractors. Experimental results on two real-world datasets verify the benefits of re-labeling noisy instance, and show that the proposed model significantly outperforms the state-of-the-art entity and relation extraction methods.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2004.09930)
* **code**:
* **dataset**:Wiki-KBP,BioInfer
* **ppt/video**:
* **curator**:Shuwei Yuan


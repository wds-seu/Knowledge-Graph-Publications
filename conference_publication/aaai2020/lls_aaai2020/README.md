#  Self-­‐Attention Enhanced Selective Gate with Entity-­‐Aware Embedding for Distantly Supervised Relation Extraction

* **author**: Yang Li, Guodong Long, Tao Shen, Tianyi Zhou, Lina Yao, Huan Huo, Jing Jiang
* **abstract**:Distantly supervised relation extraction intrinsically suffers from noisy labels due to the strong assumption of distant supervision. Most prior works adopt a selective attention mechanism over sentences in a bag to denoise from wrongly labeled data, which however could be incompetent when there is only one sentence in a bag. In this paper, we propose a brand-new light-weight neural framework to address the distantly supervised relation extraction problem and alleviate the defects in previous selective attention framework. Specifically, in the proposed framework, 1) we use an entity-aware word embedding method to integrate both relative position information and head/tail entity embeddings, aiming to highlight the essence of entities for this task; 2) we develop a self-attention mechanism to capture the rich contextual dependencies as a complement for local dependencies captured by piecewise CNN; and 3) instead of using selective attention, we design a pooling-equipped gate, which is based on rich contextual representations, as an aggregator to generate bag-level representation for final relation classification. Compared to selective attention, one major advantage of the proposed gating mechanism is that, it performs stably and promisingly even if only one sentence appears in a bag and thus keeps the consistency across all training examples. The experiments on NYT dataset demonstrate that our approach achieves a new state-of-the-art performance in terms of both AUC and top-n precision metrics.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1911.11899)
* **code**:
* **dataset**:NYT
* **ppt/video**:
* **curator**:Shuwei Yuan
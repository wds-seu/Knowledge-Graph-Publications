# Generative Adversarial Zero-Shot Relational Learning for Knowledge Graphs

* **author**: Pengda Qin, Xin Wang, Wenhu Chen, Chunyun Zhang, Weiran Xu, William Yang Wang
* **abstract**:Large-scale knowledge graphs (KGs) are shown to become more important in current information systems. To expand the coverage of KGs, previous studies on knowledge graph completion need to collect adequate training instances for newly-added relations. In this paper, we consider a novel formulation, zero-shot learning, to free this cumbersome curation. For newly-added relations, we attempt to learn their semantic features from their text descriptions and hence recognize the facts of unseen relations with no examples being seen. For this purpose, we leverage Generative Adversarial Networks (GANs) to establish the connection between text and knowledge graph domain: The generator learns to generate the reasonable relation embeddings merely with noisy text descriptions. Under this setting, zero-shot learning is naturally converted to a traditional supervised classification task. Empirically, our method is model-agnostic that could be potentially applied to any version of KG embeddings, and consistently yields performance improvements on NELL and Wiki dataset.
* **keywords**:
* **interpretation**:[link](https://blog.csdn.net/qq_38382642/article/details/104109825)
* **pdf**:[link](https://arxiv.org/pdf/2001.02332)
* **code**:
* **dataset**:NELL_ZS,Wiki-ZS
* **ppt/video**:
* **curator**:Shuwei Yuan
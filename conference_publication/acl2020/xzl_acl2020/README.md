# ReInceptionE: Relation-Aware Inception Network with Joint Local-Global Structural Information for Knowledge Graph Embedding

* **author**: Zhiwen Xie, Guangyou Zhou, Jin Liu, Jimmy Xiangji Huang
* **abstract**:The goal of Knowledge graph embedding (KGE) is to learn how to represent the low dimensional vectors for entities and relations based on the observed triples. The conventional shallow models are limited to their expressiveness. ConvE (Dettmers et al., 2018) takes advantage of CNN and improves the expressive power with parameter efficient operators by increasing the interactions between head and relation embeddings. However, there is no structural information in the embedding space of ConvE, and the performance is still limited by the number of interactions. The recent KBGAT (Nathani et al., 2019) provides another way to learn embeddings by adaptively utilizing structural information. In this paper, we take the benefits of ConvE and KBGAT together and propose a Relation-aware Inception network with joint local-global structural information for knowledge graph Embedding (ReInceptionE). Specifically, we first explore the Inception network to learn query embedding, which aims to further increase the interactions between head and relation embeddings. Then, we propose to use a relation-aware attention mechanism to enrich the query embedding with the local neighborhood and global entity information. Experimental results on both WN18RR and FB15k-237 datasets demonstrate that ReInceptionE achieves competitive performance compared with state-of-the-art methods.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://www.aclweb.org/anthology/2020.acl-main.526.pdf)
* **code**:[github](https://github.com/JuneTse/ReInceptionE)
* **dataset**:FB15k-237,WN18RR
* **ppt/video**:
* **curator**:Shuwei Yuan


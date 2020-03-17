# Collaborative Policy Learning for Open Knowledge Graph Reasoning

- **author**:  Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren

- **abstract**: In recent years, there has been a surge of interests in interpretable graph reasoning methods. However, these models often suffer from limited performance when working on sparse and incomplete graphs, due to the lack of evidential paths that can reach target entities. Here we study open knowledge graph reasoning---a task that aims to reason for missing facts over a graph augmented by a background text corpus. A key challenge of the task is to filter out "irrelevant" facts extracted from corpus, in order to maintain an effective search space during path inference. We propose a novel reinforcement learning framework to train two collaborative agents jointly, i.e., a multi-hop graph reasoner and a fact extractor. The fact extraction agent generates fact triples from corpora to enrich the graph on the fly; while the reasoning agent provides feedback to the fact extractor and guides it towards promoting facts that are helpful for the interpretable reasoning. Experiments on two public datasets demonstrate the effectiveness of the proposed approach. Source code and datasets used in this paper can be downloaded at [this https URL](https://github.com/shanzhenren/CPL) 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1909.00230)

- **code**: [code](https://github.com/shanzhenren/CPL)

- **dataset**: FB60K-NYT10,UMLS-PubMed

- **ppt/video**:

- **curator**: Yawen Dai
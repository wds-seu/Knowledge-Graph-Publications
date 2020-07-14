# Inductive Relation Prediction by Subgraph Reasoning
- **author**:  Komal K. Teru, Etienne G. Denis, William L. Hamilton
- **abstract**: The dominant paradigm for relation prediction in knowledge graphs involves learning and operating on latent representations (i.e., embeddings) of entities and relations. However, these embeddingbased methods do not explicitly capture the compositional logical rules underlying the knowledge graph, and they are limited to the transductive setting, where the full set of entities must be known during training. Here, we propose a graph neural network based relation prediction framework, GraIL, that reasons over local subgraph structures and has a strong inductive bias to learn entity-independent relational semantics. Unlike embedding-based models, GraIL is naturally inductive and can generalize to unseen entities and graphs after training. We provide theoretical proof and strong empirical evidence that GraIL can represent a useful subset of first-order logic and show that GraIL outperforms existing rule-induction baselines in the inductive setting. We also demonstrate significant gains obtained by ensembling GraIL with various knowledge graph embedding methods in the transductive setting, highlighting the complementary inductive bias of our method.
- **keywords**: 
- **interpretation**: []()
- **pdf**: [paper](https://proceedings.icml.cc/static/paper_files/icml/2020/5209-Paper.pdf)
- **code**: 
- **dataset**:  WN18RR, FB15k-237, NELL-995
- **ppt/video**:
- **curator**: Mengya Ji

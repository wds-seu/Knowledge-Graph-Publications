# KagNet: Knowledge-Aware Graph Networks for Commonsense Reasoning

- **author**:Bill Yuchen Lin, Xinyue Chen, Jamin Chen, Xiang Ren

- **abstract**: Commonsense reasoning aims to empower machines with the human ability to make presumptions about ordinary situations in our daily life. In this paper, we propose a textual inference framework for answering commonsense questions, which effectively utilizes external, structured commonsense knowledge graphs to perform explainable inferences. The framework first grounds a question-answer pair from the semantic space to the knowledge-based symbolic space as a schema graph, a related sub-graph of external knowledge graphs. It represents schema graphs with a novel knowledge-aware graph network module named KagNet, and finally scores answers with graph representations. Our model is based on graph convolutional networks and LSTMs, with a hierarchical path-based attention mechanism. The intermediate attention scores make it transparent and interpretable, which thus produce trustworthy inferences. Using ConceptNet as the only external resource for Bert-based models, we achieved state-of-the-art performance on the CommonsenseQA, a large-scale dataset for commonsense reasoning. 

- **keywords**:

- **interpretation**:[review](https://zhuanlan.zhihu.com/p/100752993)

- **pdf**: [pdf](https://arxiv.org/pdf/1909.02151)

- **code**: [code](https://github.com/INK-USC/KagNet)

- **dataset**: CommonsenseQA

- **ppt/video**:

- **curator**: Yawen Dai
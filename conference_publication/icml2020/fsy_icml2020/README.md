# Active Learning on Attributed Graphs via Graph Cognizant Logistic Regression and Preemptive Query Generation
- **author**: Florence Regol, Soumyasundar Pal, Yingxue Zhang, Mark Coates
- **abstract**: Node classification in attributed graphs is an important task in multiple practical settings, but it can often be difficult or expensive to obtain labels. Active learning can improve the achieved classification performance for a given budget on the number of queried labels. The best existing methods are based on graph neural networks, but they often perform poorly unless a sizeable validation set of labelled nodes is available in order to choose good hyperparameters. We propose a novel graph-based active learning algorithm for the task of node classification in attributed graphs; our algorithm uses graph cognizant logistic regression, equivalent to a linearized graphconvolutional neural network (GCN), for the prediction phase and maximizes the expected error reduction in the query phase. To reduce the delay experienced by a labeller interacting with the system, we derive a preemptive querying system that calculates a new query during the labelling process, and to address the setting where learning starts with almost no labelled data, we also develop a hybrid algorithm that performs adaptive model averaging of label propagation and linearized GCN inference. We conduct experiments on five public benchmark datasets, demonstrating a significant improvement over state-of-the-art approaches and illustrate the practical value of the method by applying it to a private microwave link network dataset.
- **keywords**: 
- **interpretation**: []()
- **pdf**: [paper](https://proceedings.icml.cc/static/paper_files/icml/2020/321-Paper.pdf)
- **code**: 
- **dataset**:  Cora, Citeseer, Pubmed, Am-comp., Am-photo, Microwave
- **ppt/video**:
- **curator**: Mengya Ji

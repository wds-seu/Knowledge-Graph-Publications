# Convolutional 2D Knowledge Graph Embeddings
* **author**: Pasquale Minervini, Pontus Stenetorp, Sebastian Riedel
* **abstract**: Link prediction for knowledge graphs is the task of predicting missing relationships between entities. Previous work on link prediction has focused on shallow, fast models which can scale to large knowledge graphs. However, these models learn less expressive features than deep, multi-layer models -- which potentially limits performance. In this work, we introduce ConvE, a multi-layer convolutional network model for link prediction, and report state-of-the-art results for several established datasets. We also show that the model is highly parameter efficient, yielding the same performance as DistMult and R-GCN with 8x and 17x fewer parameters. Analysis of our model suggests that it is particularly effective at modelling nodes with high indegree -- which are common in highly-connected, complex knowledge graphs such as Freebase and YAGO3. In addition, it has been noted that the WN18 and FB15k datasets suffer from test set leakage, due to inverse relations from the training set being present in the test set -- however, the extent of this issue has so far not been quantified. We find this problem to be severe: a simple rule-based model can achieve state-of-the-art results on both WN18 and FB15k. To ensure that models are evaluated on datasets where simply exploiting inverse relations cannot yield competitive results, we investigate and validate several commonly used datasets -- deriving robust variants where necessary. We then perform experiments on these robust datasets for our own and several previously proposed models and find that ConvE achieves state-of-the-art Mean Reciprocal Rank across most datasets.
* **keywords**: 
* **interpretation**: []()
* **pdf**: [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17366/15884)
* **code**:
* **dataset**:
* **ppt/video**:
* **curation**: Jiong Zhang 

# Attention Guided Graph Convolutional Networks for Relation Extraction

* **author**: Zhijiang Guo, Yan Zhang, Wei Lu
* **abstract**: Dependency trees convey rich structural information that is proven useful for extracting relations among entities in text. However, how to effectively make use of relevant information while ignoring irrelevant information from the dependency trees remains a challenging research question. Existing approaches employing rule based hard-pruning strategies for selecting relevant partial dependency structures may not always yield optimal results. In this work, we propose Attention Guided Graph Convolutional Networks (AGGCNs), a novel model which directly takes full dependency trees as inputs. Our model can be understood as a soft-pruning approach that automatically learns how to selectively attend to the relevant sub-structures useful for the relation extraction task. Extensive results on various tasks including cross-sentence n-ary relation extraction and large-scale sentence-level relation extraction show that our model is able to better leverage the structural information of the full dependency trees, giving significantly better results than previous approaches.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://www.aclweb.org/anthology/P19-1024.pdf)
* **code**: [github](https://github.com/Cartus/AGGCN)
* **dataset**: TACRED, Semeval2010-10 Task 8
* **ppt/video**:
* **curator**: Shuwei Yuan
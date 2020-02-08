# InteractE: Improving Convolution-­‐based Knowledge Graph Embeddings by Increasing Feature Interactions

* **author**:Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Nilesh Agrawal, Partha Talukdar
* **abstract**:Most existing knowledge graphs suffer from incompleteness, which can be alleviated by inferring missing links based on known facts. One popular way to accomplish this is to generate low-dimensional embeddings of entities and relations, and use these to make inferences. ConvE, a recently proposed approach, applies convolutional filters on 2D reshapings of entity and relation embeddings in order to capture rich interactions between their components. However, the number of interactions that ConvE can capture is limited. In this paper, we analyze how increasing the number of these interactions affects link prediction performance, and utilize our observations to propose InteractE. InteractE is based on three key ideas -- feature permutation, a novel feature reshaping, and circular convolution. Through extensive experiments, we find that InteractE outperforms state-of-the-art convolutional link prediction baselines on FB15k-237. Further, InteractE achieves an MRR score that is 9%, 7.5%, and 23% better than ConvE on the FB15k-237, WN18RR and YAGO3-10 datasets respectively. The results validate our central hypothesis -- that increasing feature interaction is beneficial to link prediction performance. We make the source code of InteractE available to encourage reproducible research.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1911.00219)
* **code**:[github](https://github.com/malllabiisc/InteractE)
* **dataset**:FB15k-237,WN18RR,YAGO3-10
* **ppt/video**:
* **curator**:Shuwei Yuan
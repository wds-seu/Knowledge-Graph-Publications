# Variational Knowledge Graph Reasoning
* **author**: Wenhu Chen, Wenhan Xiong, Xifeng Yan, William Yang Wang
* **abstract**: Inferring missing links in knowledge graphs (KG) has attracted a lot of attention from the research community. In this paper, we tackle a practical query answering task involving predicting the relation of a given entity pair. We frame this prediction problem as an inference problem in a probabilistic graphical model and aim at resolving it from a variational inference perspective. In order to model the relation between the query entity pair, we assume that there exists an underlying latent variable (paths connecting two nodes) in the KG, which carries the equivalent semantics of their relations. However, due to the intractability of connections in large KGs, we propose to use variation inference to maximize the evidence lower bound. More specifically, our framework (Diva) is composed of three modules, i.e. a posterior approximator, a prior (path finder), and a likelihood (path reasoner). By using variational inference, we are able to incorporate them closely into a unified architecture and jointly optimize them to perform KG reasoning. With active interactions among these sub-modules, Diva is better at handling noise and coping with more complex reasoning scenarios. In order to evaluate our method, we conduct the experiment of the link prediction task on multiple datasets and achieve state-of-the-art performances on both datasets.
* **keywords**: 
* **interpretation**: [CSDN](https://blog.csdn.net/damuge2/article/details/88344915)
* **pdf**: [paper](https://www.aclweb.org/anthology/N18-1165.pdf)
* **code**: 
* **dataset**: [NELL-995](http://cs.ucsb.edu/~xwhan/datasets/NELL-995.zip) , [FB15k-237](https://drive.google.com/file/d/1klWL11nW3ZS6b2MtLW0MHnXu-XlJqDyA/view?usp=sharing)
* **ppt/video**: [video](http://vimeo.com/277673049)
* **curation**: Xiaoyu Shang

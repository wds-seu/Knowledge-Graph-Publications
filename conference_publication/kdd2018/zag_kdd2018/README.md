# Adversarial Attacks on Neural Networks for Graph Data
- **author**: Daniel Zügner, Amir Akbarnejad, Stephan Günnemann
- **abstract**: Deep learning models for graphs have achieved strong performance for the task of node classification. Despite their proliferation, currently there is no study of their robustness to adversarial attacks. Yet, in domains where they are likely to be used, e.g. the web, adversaries are common. Can deep learning models for graphs be easily fooled? In this work, we introduce the first study of adversarial attacks on attributed graphs, specifically focusing on models exploiting ideas of graph convolutions. In addition to attacks at test time, we tackle the more challenging class of poisoning/causative attacks, which focus on the training phase of a machine learning model.We generate adversarial perturbations targeting the node's features and the graph structure, thus, taking the dependencies between instances in account. Moreover, we ensure that the perturbations remain unnoticeable by preserving important data characteristics. To cope with the underlying discrete domain we propose an efficient algorithm Nettack exploiting incremental computations. Our experimental study shows that accuracy of node classification significantly drops even when performing only few perturbations. Even more, our attacks are transferable: the learned attacks generalize to other state-of-the-art node classification models and unsupervised approaches, and likewise are successful even when only limited knowledge about the graph is given.
- **keywords**: Adversarial machine learning, graph mining, network mining, graph convolutional networks, semi-supervised learning
- **interpretation**:
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3219819.3220078?download=true)
- **code**: [code](https://github.com/danielzuegner/nettack)
- **dataset**: Cora-ML, CiteSeer, Pol.Blogs
- **ppt/video**:
- **curator**: Mengya Ji

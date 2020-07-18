# Multi-Channel Graph Neural Networks
* **author**: Kaixiong Zhou, Qingquan Song, Xiao Huang, Daochen Zha, Na Zou, Xia Hu
* **abstract**: The classification of graph-structured data has be-come increasingly crucial in many disciplines. It has been observed that the implicit or explicit hierarchical community structures preserved in real-world graphs could be useful for downstream classification applications. A straightforward way to leverage the hierarchical structure is to make use the pooling algorithms to cluster nodes into fixed groups, and shrink the input graph layer by layer to learn the pooled graphs.However, the pool shrinking discards the graph details to make it hard to distinguish two non-isomorphic graphs, and the fixed clustering ignores the inherent multiple characteristics of nodes. To compensate the shrinking loss and learn the various nodes’ characteristics, we propose the multi-channel graph neural networks (MuchGNN). Motivated by the underlying mechanisms developed in convolutional neural networks, we define the tailored graph convolutions to learn a series of graph channels at each layer, and shrink the graphs hierarchically to en-code the pooled structures. Experimental results on real-world datasets demonstrate the superiority of MuchGNN over the state-of-the-art methods.
* **keywords**: Graph Convolutional Network, multi-channel
* **interpretation**: [来源: CSDN](https://blog.csdn.net/todoooooo/article/details/106503700)
* **pdf**: [link](https://www.ijcai.org/Proceedings/2020/188)
* **code**: 
* **dataset**: PTC, DD, PROTEINS, COLLAB, IMDBBINARY, IMDB-MULTI, REDDIT-MULTI-12K
* **ppt/video**:
* **curation**: Jiong Zhang 
# Knowledge Graph Convolutional Networks for Recommender Systems
- **author**: Hongwei Wang, Miao Zhao, Xing Xie, Wenjie Li, Minyi Guo  
- **abstract**: To alleviate sparsity and cold start problem of collaborative filtering based recommender systems, researchers and engineers usually collect attributes of users and items, and design delicate algorithms to exploit these additional information. In general, the attributes are not isolated but connected with each other, which forms a knowledge graph (KG). In this paper, we propose Knowledge Graph Convolutional Networks (KGCN), an end-to-end framework that captures inter-item relatedness effectively by mining their associated attributes on the KG. To automatically discover both high-order structure information and semantic information of the KG, we sample from the neighbors for each entity in the KG as their receptive field, then combine neighborhood information with bias when calculating the representation of a given entity. The receptive field can be extended to multiple hops away to model high-order proximity information and capture users' potential long-distance interests. Moreover, we implement the proposed KGCN in a minibatch fashion, which enables our model to operate on large datasets and KGs. We apply the proposed model to three datasets about movie, book, and music recommendation, and experiment results demonstrate that our approach outperforms strong recommender baselines.
- **keywords**: Recommender systems; Knowledge graph; Graph convolutional networks
- **interpretation**: [OpenKG](https://mp.weixin.qq.com/s/UDKvVrpvgbX-9JzA75qslQ)
- **pdf**: [paper](https://arxiv.org/pdf/1904.12575.pdf)
- **code**: [github](https://github.com/hwwang55/KGCN)
- **dataset**:  MovieLens-20M, Book-Crossing, Last.FM
- **ppt/video**:
- **curator**: Xiaoyu Shang 

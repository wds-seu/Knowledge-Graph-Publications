# DKN: Deep Knowledge-Aware Network for News Recommendation 
- **author**: Hongwei Wang, Fuzheng Zhang, Xing Xie, Minyi Guo   
- **abstract**: Online news recommender systems aim to address the information explosion of news and make personalized recommendation for users. In general, news language is highly condensed, full of knowledge entities and common sense. However, existing methods are unaware of such external knowledge and cannot fully discover latent knowledge-level connections among news. The recommended results for a user are consequently limited to simple patterns and cannot be extended reasonably. To solve the above problem, in this paper, we propose a deep knowledge-aware network (DKN) that incorporates knowledge graph representation into news recommendation. DKN is a content-based deep recommendation framework for click-through rate prediction. The key component of DKN is a multi-channel and word-entity-aligned knowledge-aware convolutional neural network (KCNN) that fuses semantic-level and knowledge-level representations of news. KCNN treats words and entities as multiple channels, and explicitly keeps their alignment relationship during convolution. In addition, to address users» diverse interests, we also design an attention module in DKN to dynamically aggregate a user»s history with respect to current candidate news. Through extensive experiments on a real online news platform, we demonstrate that DKN achieves substantial gains over state-of-the-art deep recommendation models. We also validate the efficacy of the usage of knowledge in DKN. 
- **keywords**: News recommendation; knowledge graph representation; deep neural networks; attention model
- **interpretation**: [知乎](https://zhuanlan.zhihu.com/p/34919142)
- **pdf**: [paper](https://arxiv.org/pdf/1801.08284v1)
- **code**: [github](https://github.com/hwwang55/DKN)
- **dataset**: BingNews
- **ppt/video**:
- **curator**: Xiaoyu Shang 

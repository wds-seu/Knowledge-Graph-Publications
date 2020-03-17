# Interaction Embeddings for Prediction and Explanation in Knowledge Graphs
* **author**: Wen Zhang, Bibek Paudel, Wei Zhang, Abraham Bernstein, Huajun Chen
* **abstract**: Knowledge graph embedding aims to learn distributed representations for entities and relations, and is proven to be effective in many applications. Crossover interactions -- bi-directional effects between entities and relations --- help select related information when predicting a new triple, but haven't been formally discussed before. In this paper, we propose CrossE, a novel knowledge graph embedding which explicitly simulates crossover interactions. It not only learns one general embedding for each entity and relation as most previous methods do, but also generates multiple triple specific embeddings for both of them, named interaction embeddings. We evaluate embeddings on typical link prediction tasks and find that CrossE achieves state-of-the-art results on complex and more challenging datasets. Furthermore, we evaluate embeddings from a new perspective -- giving explanations for predicted triples, which is important for real applications. In this work, an explanation for a triple is regarded as a reliable closed-path between the head and the tail entity. Compared to other baselines, we show experimentally that CrossE, benefiting from interaction embeddings, is more capable of generating reliable explanations to support its predictions.
* **keywords**:Crossover interactions, link prediction 
* **interpretation**: [来源: 阿里云](https://yq.aliyun.com/articles/714553)
* **pdf**: [link](https://dl.acm.org/doi/pdf/10.1145/3289600.3291014?download=true)
* **code**: 
* **dataset**:WN18, FB15K, FB15K-237
* **ppt/video**:
* **curation**: Jiong Zhang 
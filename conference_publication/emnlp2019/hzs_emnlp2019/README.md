# Improving Distantly-Supervised Relation Extraction with Joint Label Embedding

- **author**:Linmei Hu, Luhao Zhang, Chuan Shi, Liqiang Nie, Weili Guan,Cheng Yang

- **abstract**: Distantly-supervised relation extraction has proven to be effective to find relational facts from texts. However, the existing approaches treat labels as independent and meaningless one-hot vectors, which cause a loss of potential label information for selecting valid instances. In this paper, we propose a novel multi-layer attention-based model to improve relation extraction with joint label embedding. The model makes full use of both structural information from Knowledge Graphs and textual information from entity descriptions to learn label embeddings through gating integration while avoiding the imposed noise with an attention mechanism. Then the learned label embeddings are used as another atten- tion over the instances (whose embeddings are also enhanced with the entity descriptions) for improving relation extraction. Extensive experiments demonstrate that our model significantly outperforms state-of-the-art methods. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1395.pdf )

- **code**: 

- **dataset**: NYT-FB60K, GIDS-FB8K

- **ppt/video**:

- **curator**: Yawen Dai
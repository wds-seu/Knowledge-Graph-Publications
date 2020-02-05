# A Non-commutative Bilinear Model for Answering Path Queries in Knowledge Graphs

- **author**:Katsuhiko Hayashi, Masashi Shimbo
- **abstract**: Bilinear diagonal models for knowledge graph embedding (KGE), such as DistMult and ComplEx, balance expressiveness and computational efficiency by representing relations as diagonal matrices. Although they perform well in predicting atomic relations, composite relations (relation paths) cannot be modeled naturally by the product of relation matrices, as the product of diagonal matrices is commutative and hence invariant with the order of relations. In this paper, we propose a new bilinear KGE model, called BlockHolE, based on block circulant matrices. In BlockHolE, relation matrices can be non-commutative, allowing composite relations to be modeled by matrix product. The model is parameterized in a way that covers a spectrum ranging from diagonal to full relation matrices. A fast computation technique is developed on the basis of the duality of the Fourier transform of circulant matrices. 
- **keywords**:
- **interpretation**:待补充
- **pdf**: [pdf](https://arxiv.org/pdf/1909.01567)
- **code**: 
- **dataset**: WordNet,Freebase 
- **ppt/video**:
- **curator**: Yawen Dai
# Cross-Sentence N-ary Relation Extraction using Lower-Arity Universal Schemas

- **author**:Kosuke Akimoto,Takuya Hiraoka,Kunihiko Sadamasa,Mathias Niepert

- **abstract**: Most existing relation extraction approaches exclusively target binary relations, and n-ary relation extraction is relatively unexplored. Current state-of-the-art n-ary relation extraction method is based on a supervised learning approach and, therefore, may suffer from the lack of sufficient relation labels. In this paper, we propose a novel approach to cross-sentence n-ary relation extraction based on universal schemas. To alleviate the sparsity problem and to leverage inherent decomposability of n-ary relations, we propose to learn relation representations of lower-arity facts that result from decomposing higher-arity facts. The proposed method computes a score of a new n-ary fact by aggregating scores of its decomposed lower-arity facts. We conduct experiments with datasets for ternary relation extraction and empirically show that our method improves the n-ary relation extraction performance compared to previous methods. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1645.pdf )

- **code**: [code](https://github.com/aurtg/nary-relation-extraction-decomposed)

- **dataset**: two new n-ary cross-sentence relation extraction datasets (dubbed with Wiki-90k and WF-20k)

- **ppt/video**:

- **curator**: Yawen Dai
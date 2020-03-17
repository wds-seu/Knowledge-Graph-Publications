# Jointly Learning Entity and Relation Representations for Entity Alignment

- **author**: Yuting Wu,Xiao Liu,Yansong Feng,Zheng Wang, Dongyan Zhao

- **abstract**:  Entity alignment is a viable means for integrating heterogeneous knowledge among different knowledge graphs (KGs). Recent developments in the field often take an embedding-based approach to model the structural information of KGs so that entity alignment can be easily performed in the embedding space. However, most existing works do not explicitly utilize useful relation representations to assist in entity alignment, which, as we will show in the paper, is a simple yet effective way for improving entity alignment. This paper presents a novel joint learning framework for entity alignment. At the core of our approach is a Graph Convolutional Network (GCN) based framework for learning both entity and relation representations. Rather than relying on pre-aligned relation seeds to learn relation representations, we first approximate them using entity embeddings learned by the GCN. We then incorporate the relation approximation into entities to iteratively learn better representations for both. Experiments performed on three real-world cross-lingual datasets show that our approach substantially outperforms state-of-the-art entity alignment methods.  

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1909.09317)

- **code**: [code](https://github.com/StephanieWyt/HGCN-JE-JR)

- **dataset**: DBP15K 

- **ppt/video**:

- **curator**: Yawen Dai
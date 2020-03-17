# Semi-supervised Entity Alignment via Joint Knowledge Embedding Model and Cross-graph Model

- **author**:Chengjiang Li ,Yixin Cao ,Lei Hou ,Jiaxin Shi ,Juanzi Li ,Tat-Seng Chua

- **abstract**: Entity alignment aims at integrating complementary knowledge graphs (KGs) from different sources or languages, which may benefit many knowledge-driven applications. It is challenging due to the heterogeneity of KGs and limited seed alignments. In this paper, we propose a semi-supervised entity alignment method by joint Knowledge Embedding model and Cross-Graph model (KECG). It can make better use of seed alignments to propagate over the entire graphs with KG-based constraints. Specifically, as for the knowledge embedding model, we utilize TransE to implicitly complete two KGs towards consistency and learn relational constraints between entities. As for the cross-graph model, we extend Graph Attention Network (GAT) with projection constraint to robustly encode graphs, and two KGs share the same GAT to transfer structural knowledge as well as to ignore unimportant neighbors for alignment via attention mechanism. Results on publicly available datasets as well as further analysis demonstrate the effectiveness of KECG. Our codes can be found in https: //github.com/THU-KEG/KECG. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1274.pdf )

- **code**: [code](https://github.com/THU-KEG/KECG)  

- **dataset**: DBP15K, DWY100K

- **ppt/video**:

- **curator**: Yawen Dai
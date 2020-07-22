# TransRHS: A Representation Learning Method for Knowledge Graphs with Relation Hierarchical Structure
* **author**: Fuxiang Zhang, Xin Wang, Zhao Li, Jianxin Li
* **abstract**: Representation learning of knowledge graphs aims to project both entities and relations as vectors in a continuous low-dimensional space. Relation Hierarchical Structure (RHS), which is constructed by a generalization relationship named subRelationOf between relations, can improve the overall performance of knowledge representation learning. However, most of the existing methods ignore this critical information, and a straightforward way of considering RHS may have a negative effect on the embeddings and thus reduce the model performance. In this paper, we propose a novel method named TransRHS, which is able to incorporate RHS seamlessly into the embeddings. More specifically, TransRHS encodes each relation as a vector together with a relation-specific sphere in the same space. Our TransRHS employs the relative positions among the vectors and spheres to model the subRelationOf, which embodies the inherent generalization relationships among relations. We evaluate our model on two typical tasks, i.e., link prediction and triple classification. The experimental results show that our TransRHS model significantly outperforms all baselines on both tasks, which verifies that the RHS information is significant to representation learning of knowledge graphs, and TransRHS can effectively and efficiently fuse RHS into knowledge graph embeddings.
* **keywords**: Representation Learning, Relation Hierarchical Structure (RHS)
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.ijcai.org/Proceedings/2020/413)
* **code**: 
* **dataset**: Sport, Location
* **ppt/video**:
* **curation**: Jiong Zhang 
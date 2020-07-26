# Improving Knowledge Graph Embedding Using Simple Constraints

* **author**：Boyang Ding, Quan Wang, Bin Wang, Li Guo
* **abstract**: Embedding knowledge graphs (KGs) into continuous vector spaces is a focus of current research. Early works performed this task via simple models developed over KG triples. Recent attempts focused on either designing more complicated triple scoring models, or incorporating extra information beyond triples. This paper, by contrast, investigates the potential of using very simple constraints to improve KG embedding. We examine non-negativity constraints on entity representations and approximate entailment constraints on relation representations. The former help to learn compact and interpretable representations for entities. The latter further encode regularities of logical entailment between relations into their distributed representations. These constraints impose prior beliefs upon the structure of the embedding space, without negative impacts on efficiency or scalability. Evaluation on WordNet, Freebase, and DBpedia shows that our approach is simple yet surprisingly effective, significantly and consistently outperforming competitive baselines. The constraints imposed indeed improve model interpretability, leading to a substantially increased structuring of the embedding space. Code and data are available at https://github.com/iieir-km/ComplEx-NNE_AER.
* **keywords**: 
* **interpretation**:[link](https://zhuanlan.zhihu.com/p/61143831) 
* **pdf**:  [link](https://www.aclweb.org/anthology/P18-1011.pdf)
* **code**: [link](https://github.com/iieir-km/ComplEx-NNE_AER)
* **dataset**: WN18, FB15K
* **ppt/video**: 
* **curator**: Chang Liu

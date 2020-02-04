# Explainable Reasoning over Knowledge Graphs for Recommendation  
- **author**: Xiang Wang, Dingxian Wang, Canran Xu, Xiangnan He, Yixin Cao, Tat-Seng Chua    
- **abstract**: Incorporating knowledge graph into recommender systems has attracted increasing attention in recent years. By exploring the interlinks within a knowledge graph, the connectivity between users and items can be discovered as paths, which provide rich and complementary information to user-item interactions. Such connectivity not only reveals the semantics of entities and relations, but also helps to comprehend a user’s interest. However, existing efforts have not fully explored this connectivity to infer user preferences, especially in terms of modeling the sequential dependencies within and holistic semantics of a path.
In this paper, we contribute a new model named Knowledgeaware Path Recurrent Network (KPRN) to exploit knowledge graph for recommendation. KPRN can generate path representations by composing the semantics of both entities and relations. By leveraging the sequential dependencies within a path, we allow effective reasoning on paths to infer the underlying rationale of a user-item interaction. Furthermore, we design a new weighted pooling operation to discriminate the strengths of different paths in connecting a user with an item, endowing our model with a certain level of explainability. We conduct extensive experiments on two datasets about movie and music, demonstrating significant improvements over state-of-the-art solutions Collaborative Knowledge Base Embedding and Neural Factorization Machine.  
- **keywords**: 
- **interpretation**: [知乎-RUC AI BOX](https://zhuanlan.zhihu.com/p/51000072)
- **pdf**: [paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4470/4348)
- **code**: [github](https://github.com/eBay/KPRN)
- **dataset**: MovieLens-1M, IMDb, KKBox  
- **ppt/video**:
- **curator**: Xiaoyu Shang 

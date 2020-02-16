# Unifying Knowledge Graph Learning and Recommendation: Towards a Better Understanding of User Preferences    
- **author**: Yixin Cao, Xiang Wang, Xiangnan He, Zikun Hu, Tat-Seng Chua  
- **abstract**: Incorporating knowledge graph (KG) into recommender system is promising in improving the recommendation accuracy and explainability. However, existing methods largely assume that a KG is complete and simply transfer the ”knowledge” in KG at the shallow level of entity raw data or embeddings. This may lead to suboptimal performance, since a practical KG can hardly be complete, and it is common that a KG has missing facts, relations, and entities. Thus, we argue that it is crucial to consider the incomplete nature of KG when incorporating it into recommender system.  
In this paper, we jointly learn the model of recommendation and knowledge graph completion. Distinct from previous KG-based recommendation methods, we transfer the relation information in KG, so as to understand the reasons that a user likes an item. As an example, if a user has watched several movies directed by (relation) the same person (entity), we can infer that the director relation plays a critical role when the user makes the decision, thus help to understand the user's preference at a finer granularity.  
Technically, we contribute a new translation-based recommendation model, which specially accounts for various preferences in translating a user to an item, and then jointly train it with a KG completion model by combining several transfer schemes. Extensive experiments on two benchmark datasets show that our method outperforms state-of-the-art KG-based recommendation methods. Further analysis verifies the positive effect of joint training on both tasks of recommendation and KG completion, and the advantage of our model in understanding user preference. We publish our project at https://github.com/TaoMiner/joint-kg-recommender.
- **keywords**: Item Recommendation; Knowledge Graph; Embedding; JointModel; 
- **interpretation**: 
- **pdf**: [paper](https://arxiv.org/pdf/1902.06236v1.pdf)
- **code**: [github](https://github.com/TaoMiner/joint-kg-recommender)
- **dataset**: MovieLens-1m, DBbook20142 
- **ppt/video**:
- **curator**: Xiaoyu Shang

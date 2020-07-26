# Auto-EM: End-to-end Fuzzy Entity-Matching using Pre-trained Deep Models and Transfer Learning
- **author**: Chen Zhao, Yeye He  
- **abstract**: Entity matching (EM), also known as entity resolution, fuzzy join, and record linkage, refers to the process of identifying records corresponding to the same real-world entities from different data sources. It is an important and long-standing problem in data integration and data mining. So far progresses have been made mainly in the form of model improvements, where models with better accuracy are developed when large amounts of training data is available. In real-world applications we find that advanced approaches can often require too many labeled examples that is expensive to obtain, which has become a key obstacle to wider adoption. 
We in this work take a different tack, proposing a transfer-learning approach to EM, leveraging pre-trained EM models from large-scale, production knowledge bases (KB). Specifically, for each entity-type in KB, (e.g., location, organization, people, etc.), we use rich synonymous names of known entities in the KB as training data, to pre-train type-detection and EM models for each type, using a novel hierarchical neural network architecture we develop. Given a new EM task, with little or no training data, we can either fine-tune or directly leverage pre-trained EM models, to build end-to-end, high-quality EM systems. Experiments on a variety of real EM tasks suggest that the pre-trained approach is effective and outperforms existing EM methods.1.
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](https://www.microsoft.com/en-us/research/uploads/prod/2019/04/Auto-EM.pdf)
- **code**: [github](https://github.com/henryzhao5852/AutoEM)
- **dataset**: Wikipedia
- **ppt/video**:
- **curator**: Xiaoyu Shang

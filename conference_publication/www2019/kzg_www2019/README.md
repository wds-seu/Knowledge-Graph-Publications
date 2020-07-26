# A Neural Bag-of-Words Modelling Framework for Link Prediction in Knowledge Bases with Sparse Connectivity
- **author**: Fanshuang Kong, Richong Zhang, Hongyu Guo, Samuel Mensah, Zhiyuan Hu, Yongyi Mao  
- **abstract**: Knowledge graphs such as DBPedia and Freebase contain sparse linkage connectivity, which poses severe challenge to link prediction between entities. In addressing this sparsity problem, our studies indicate that one needs to leverage model with low complexity to avoid overfitting the weak structural information in the graphs, requiring the simple models which can efficiently encode the entities and their description information and then effectively decode their relationships. In this paper, we present a simple and efficient model that can attain these two goals. Specifically, we use a bag-of-words model, where relevant words are aggregated using average pooling or a basic Graph Convolutional Network to encode entities into distributed embeddings. A factorization machine is then used to score the relationships between those embeddings to generate linkage predictions. Empirical studies on two real datasets confirms the efficiency of our proposed model and shows superior predictive performance over state-of-the-art approaches. 
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](https://www.researchgate.net/profile/Samuel_Mensah8/publication/333076226_A_Neural_Bag-of-Words_Modelling_Framework_for_Link_Prediction_in_Knowledge_Bases_with_Sparse_Connectivity/links/5ea68885a6fdccd79457fa7a/A-Neural-Bag-of-Words-Modelling-Framework-for-Link-Prediction-in-Knowledge-Bases-with-Sparse-Connectivity.pdf)
- **code**:
- **dataset**: DBPedia50K, FB15K-237
- **ppt/video**:
- **curator**: Xiaoyu Shang 

# TransGate: Knowledge Graph Embedding with Shared Gate Structure 
- **author**: Jun Yuan, Neng Gao, Ji Xiang    
- **abstract**: Embedding knowledge graphs (KGs) into continuous vector space is an essential problem in knowledge extraction. Current models continue to improve embedding by focusing on discriminating relation-specific information from entities with increasingly complex feature engineering. We noted that they ignored the inherent relevance between relations and tried to learn unique discriminate parameter set for each relation. Thus, these models potentially suffer from high time complexity and large parameters, preventing them from efficiently applying on real-world KGs. In this paper, we follow the thought of parameter sharing to simultaneously learn more expressive features, reduce parameters and avoid complex feature engineering. Based on gate structure from LSTM, we propose a novel model TransGate and develop shared discriminate mechanism, resulting in almost same space complexity as indiscriminate models. Furthermore, to develop a more effective and scalable model, we reconstruct the gate with weight vectors making our method has comparative time complexity against indiscriminate model. We conduct extensive experiments on link prediction and triplets classification. Experiments show that TransGate not only outperforms state-of-art baselines, but also reduces parameters greatly. For example, TransGate outperforms ConvE and RGCN with 6x and 17x fewer parameters, respectively. These results indicate that parameter sharing is a superior way to further optimize embedding and TransGate finds a better trade-off between complexity and expressivity.
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4169/4047)
- **code**: 
- **dataset**:  WordNet (Miller 1995), Freebase (Bollacker et al. 2008). 
- **ppt/video**: 
- **curator**: Xiaoyu Shang 

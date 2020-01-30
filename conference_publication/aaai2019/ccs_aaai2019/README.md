# Embedding Uncertain Knowledge Graphs  
- **author**: Xuelu Chen, Muhao Chen, Weijia Shi, Yizhou Sun, Carlo Zaniolo    
- **abstract**: Embedding models for deterministic Knowledge Graphs (KG) have been extensively studied, with the purpose of capturing latent semantic relations between entities and incorporating the structured knowledge they contain into machine learning. However, there are many KGs that model uncertain knowledge, which typically model the inherent uncertainty of relations facts with a confidence score, and embedding such uncertain knowledge represents an unresolved challenge. The capturing of uncertain knowledge will benefit many knowledge-driven applications such as question answering and semantic search by providing more natural characterization of the knowledge. In this paper, we propose a novel uncertain KG embedding model UKGE, which aims to preserve both structural and uncertainty information of relation facts in the embedding space. Unlike previous models that characterize relation facts with binary classification techniques, UKGE learns embeddings according to the confidence scores of uncertain relation facts. To further enhance the precision of UKGE, we also introduce probabilistic soft logic to infer confidence scores for unseen relation facts during training. We propose and evaluate two variants of UKGE based on different confidence score modeling strategies. Experiments are conducted on three real-world uncertain KGs via three tasks, i.e. confidence prediction, relation fact ranking, and relation fact classification. UKGE shows effectiveness in capturing uncertain knowledge by achieving promising results, and it consistently outperforms baselines on these tasks.    
- **keywords**: 
- **interpretation**:
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4210/4088)
- **code**: 
- **dataset**: CN15k, NL27k, PPI5k (extracted from ConceptNet, NELL and STRING respectively) 
- **ppt/video**:
- **curator**: Xiaoyu Shang 

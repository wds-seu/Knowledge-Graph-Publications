# Joint Entity Linking with Deep Reinforcement Learning  
- **author**: Zheng Fang, Yanan Cao, Qian Li, Dongjie Zhang, Zhenyu Zhang, Yanbing Liu  
- **abstract**: Entity linking is the task of aligning mentions to corresponding entities in a given knowledge base. Previous studies have highlighted the necessity for entity linking systems to capture the global coherence. However, there are two common weaknesses in previous global models. First, most of them calculate the pairwise scores between all candidate entities and select the most relevant group of entities as the final result. In this process, the consistency among wrong entities as well as that among right ones are involved, which may introduce noise data and increase the model complexity. Second, the cues of previously disambiguated entities, which could contribute to the disambiguation of the subsequent mentions, are usually ignored by previous models. To address these problems, we convert the global linking into a sequence decision problem and propose a reinforcement learning model which makes decisions from a global perspective. Our model makes full use of the previous referred entities and explores the long-term influence of current selection on subsequent decisions. We conduct experiments on different types of datasets, the results show that our model outperforms state-of-the-art systems and has better generalization performance. 
- **keywords**: Entity linking, reinforcement learning, joint disambiguation, knowledge base 
- **interpretation**: 
- **pdf**: [paper](https://arxiv.org/pdf/1902.00330v1.pdf)
- **code**:
- **dataset**: AIDA-CoNLL, Wikipediadatasets, ACE2004, MSNBC, AQUAINT, WNED-CWEB, WNED-WIKI, OURSELF-WIKI
- **ppt/video**:
- **curator**: Xiaoyu Shang

# ELDEN: Improved Entity Linking Using Densified Knowledge Graphs
* **author**: Priya Radhakrishnan, Partha Talukdar, Vasudeva Varma
* **abstract**: Entity Linking (EL) systems aim to automatically map mentions of an entity in text to the corresponding entity in a Knowledge Graph (KG). Degree of connectivity of an entity in the KG directly affects an EL system’s ability to correctly link mentions in text to the entity in KG. This causes many EL systems to perform well for entities well connected to other entities in KG, bringing into focus the role of KG density in EL. In this paper, we propose Entity Linking using Densified Knowledge Graphs (ELDEN). ELDEN is an EL system which first densifies the KG with co-occurrence statistics from a large text corpus, and then uses the densified KG to train entity embeddings. Entity similarity measured using these trained entity embeddings result in improved EL. ELDEN outperforms state-of-the-art EL system on benchmark datasets. Due to such densification, ELDEN performs well for sparsely connected entities in the KG too. ELDEN’s approach is simple, yet effective. We have made ELDEN’s code and data publicly available.
* **keywords**: 
* **interpretation**: [OpenKG](https://mp.weixin.qq.com/s/-0WExZHcmDZ85qHwUtYB2Q)
* **pdf**: [paper](https://www.aclweb.org/anthology/N18-1167.pdf)
* **code**: [github](https://github.com/priyaradhakrishnan0/ELDEN)
* **dataset**: TAC2010, CoNLL
* **ppt/video**: [video](http://vimeo.com/277673016)
* **curation**: Xiaoyu Shang

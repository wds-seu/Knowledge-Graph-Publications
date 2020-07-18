# Open-World Knowledge Graph Completion
* **author**: Baoxu Shi, Tim Weninger
* **abstract**: Knowledge Graphs (KGs) have been applied to many tasks including Web search, link prediction, recommendation, natural language processing, and entity linking. However, most KGs are far from complete and are growing at a rapid pace. To address these problems, Knowledge Graph Completion (KGC) has been proposed to improve KGs by filling in its missing connections. Unlike existing methods which hold a closed-world assumption, i.e., where KGs are fixed and new entities cannot be easily added, in the present work we relax this assumption and propose a new open-world KGC task. As a first attempt to solve this task we introduce an open-world KGC model called ConMask. This model learns embeddings of the entity's name and parts of its text-description to connect unseen entities to the KG. To mitigate the presence of noisy text descriptions, ConMask uses a relationship-dependent content masking to extract relevant snippets and then trains a fully convolutional neural network to fuse the extracted snippets with entities in the KG. Experiments on large data sets, both old and new, show that ConMask performs well in the open-world KGC task and even outperforms existing KGC models on the standard closed-world KGC task.
* **keywords**: Knowledge Graph Completion
* **interpretation**: [来源: OpenKG](http://blog.openkg.cn/%E8%AE%BA%E6%96%87%E6%B5%85%E5%B0%9D-open-world-knowledge-graph-completion/)
* **pdf**: [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16055/15901)
* **code**: [link](https://github.com/bxshi/ConMask)
* **dataset**: FB15K, DBPedia50k, DBPedia500k
* **ppt/video**:
* **curation**: Jiong Zhang 

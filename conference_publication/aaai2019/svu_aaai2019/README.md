# An Open-World Extension to Knowledge Graph Completion Models 
- **author**: Haseeb Shah, Johannes Villmow, Adrian Ulges, Ulrich Schwanecke, Faisal Shafait  
- **abstract**: We present a novel extension to embedding-based knowledge graph completion models which enables them to perform open-world link prediction, i.e. to predict facts for entities unseen in training based on their textual description. Our model combines a regular link prediction model learned from a knowledge graph with word embeddings learned from a textual corpus. After training both independently, we learn a transformation to map the embeddings of an entity’s name and description to the graph-based embedding space.  
In experiments on several datasets including FB20k, DBPedia50k and our new dataset FB15k-237-OWE, we demonstrate competitive results. Particularly, our approach exploits the full knowledge graph structure even when textual descriptions are scarce, does not require a joint training on graph and text, and can be applied to any embedding-based link prediction model, such as TransE, ComplEx and DistMult.
- **keywords**: 
- **interpretation**: [OpenKG](https://mp.weixin.qq.com/s/91STLMh5_EpByiq5_r0w1Q)
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4162/4040)
- **code**: [github](https://github.com/haseebs/OWE)
- **dataset**: FB20k, DBPedia50k, FB15k-237-OWE
- **ppt/video**: 
- **curator**: Xiaoyu Shang 

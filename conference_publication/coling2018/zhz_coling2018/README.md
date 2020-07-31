# An Interpretable Reasoning Network for Multi-Relation Question Answering
* **author**: Mantong Zhou, Minlie Huang, Xiaoyan Zhu
* **abstract**: Multi-relation Question Answering is a challenging task, due to the requirement of elaborated analysis on questions and reasoning over multiple fact triples in knowledge base. In this paper, we present a novel model called Interpretable Reasoning Network that employs an interpretable, hop-by-hop reasoning process for question answering. The model dynamically decides which part of an input question should be analyzed at each hop; predicts a relation that corresponds to the current parsed results; utilizes the predicted relation to update the question representation and the state of the reasoning process; and then drives the next-hop reasoning. Experiments show that our model yields state-of-the-art results on two datasets. More interestingly, the model can offer traceable and observable intermediate predictions for reasoning analysis and failure diagnosis, thereby allowing manual manipulation in predicting the final answer.
* **keywords**: Multi-relation Question Answering
* **interpretation**: [来源: PaperWeekly](https://mp.weixin.qq.com/s/e5Kb590xoDIUkv_TKW1uZA)
* **pdf**: [link](https://www.aclweb.org/anthology/C18-1171.pdf)
* **code**: 
* **dataset**: [PathQuestion (PQ)](https://github.com/zmtkeke/IRN), WorldCup2014
* **ppt/video**: 
* **curation**: Jiong Zhang 
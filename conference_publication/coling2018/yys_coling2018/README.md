# Recurrent One-Hop Predictions for Reasoning over Knowledge Graphs
* **author**: Wenpeng Yin, Yadollah Yaghoobzadeh, Hinrich Schütze
* **abstract**: Large scale knowledge graphs (KGs) such as Freebase are generally incomplete. Reasoning over multi-hop (mh) KG paths is thus an important capability that is needed for question answering or other NLP tasks that require knowledge about the world. mh-KG reasoning includes diverse scenarios, e.g., given a head entity and a relation path, predict the tail entity; or given two entities connected by some relation paths, predict the unknown relation between them. We present ROPs, recurrent one-hop predictors, that predict entities at each step of mh-KB paths by using recurrent neural networks and vector representations of entities and relations, with two benefits: (i) modeling mh-paths of arbitrary lengths while updating the entity and relation representations by the training signal at each step; (ii) handling different types of mh-KG reasoning in a unified framework. Our models show state-of-the-art for two important multi-hop KG reasoning tasks: Knowledge Base Completion and Path Query Answering
* **keywords**: multi-hop KG reasoning
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.aclweb.org/anthology/C18-1200.pdf)
* **code**: [link](https://github.com/yinwenpeng/KBPath)
* **dataset**:mh-PQA, mh-KBC
* **ppt/video**:
* **curation**: Jiong Zhang 
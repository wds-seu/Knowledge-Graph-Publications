# Reasoning on Knowledge Graphs with Debate Dynamics

* **author**: Marcel Hildebrandt, Jorge Andres Quintero Serna,Yunpu Ma,Martin Ringsquandl, Mitchell Joblin,  Volker Tresp
* **abstract**: We propose a novel method for automatic reasoning on knowledge graphs based on debate dynamics. The main idea is to frame the task of triple classification as a debate game between two reinforcement learning agents which extract arguments– paths in the knowledge graph – with the goal to promote the fact being true (thesis) or the fact being false (antithesis), respectively. Based on these arguments, a binary classifier, called the judge, decides whether the fact is true or false. The two agents can be considered as sparse, adversarial feature generators that present interpretable evidence for either the thesis or the antithesis. In contrast to other black-box methods, the arguments allow users to get an understanding of the decision of the judge. Since the focus of this work is to create an explainable method that maintains a competitive predictive accuracy, we benchmark our method on the triple classification and link prediction task. Thereby, we find that our method outperforms several baselines on the benchmark datasets FB15k-237, WN18RR, and Hetionet.We also conduct a survey and find that the extracted arguments are informative for users.
* **keywords**:
* **interpretation**:
* **pdf**: [link](https://arxiv.org/pdf/2001.00461)
* **code**：[github](https://github.com/m-hildebrandt/R2D2)
* **dataset**:FB15k-237,WN18RR
* **ppt/video**:
* **curator**:Shuwei Yuan
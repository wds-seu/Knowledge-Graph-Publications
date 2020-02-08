# K-­‐BERT: Enabling Language Representation With Knowledge Graph

* **author**: Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Qi Ju, Haotang Deng, Ping Wang
* **abstract**:Pre-trained language representation models, such as BERT, capture a general language representation from large-scale corpora, but lack domain-specific knowledge. When reading a domain text, experts make inferences with relevant knowledge. For machines to achieve this capability, we propose a knowledge-enabled language representation model (K-BERT) with knowledge graphs (KGs), in which triples are injected into the sentences as domain knowledge. However, too much knowledge incorporation may divert the sentence from its correct meaning, which is called knowledge noise (KN) issue. To overcome KN, K-BERT introduces soft-position and visible matrix to limit the impact of knowledge. K-BERT can easily inject domain knowledge into the models by equipped with a KG without pre-training by-self because it is capable of loading model parameters from the pre-trained BERT. Our investigation reveals promising results in twelve NLP tasks. Especially in domain-specific tasks (including finance, law, and medicine), K-BERT significantly outperforms BERT, which demonstrates that K-BERT is an excellent choice for solving the knowledge-driven problems that require experts.
* **keywords**:
* **interpretation**:[link](https://cloud.tencent.com/developer/article/1538627)
* **pdf**:[link](https://arxiv.org/pdf/1909.07606)
* **code**:[link](https://github.com/autoliuweijie/K-BERT)
* **dataset**:Book_review,Chnsenticorp,Shopping,Weibo,XNLI,LCQMC,NLPCC-DBQA,MSRA-NER,Finance-Q&A,Law-Q&A,Finance_NER,Medicine_NER
* **ppt/video**:
* **curator**:Shuwei Yuan
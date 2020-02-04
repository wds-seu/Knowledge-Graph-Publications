# Knowledge-aware Pronoun Coreference Resolution

* **author**: Hongming Zhang, Yan Song, Yangqiu Song, Dong Yu
* **abstract**: Resolving pronoun coreference requires knowledge support, especially for particular domains (e.g., medicine). In this paper, we explore how to leverage different types of knowledge to better resolve pronoun coreference with a neural model. To ensure the generalization ability of our model, we directly incorporate knowledge in the format of triplets, which is the most common format of modern knowledge graphs, instead of encoding it with features or rules as that in conventional approaches. Moreover, since not all knowledge is helpful in certain contexts, to selectively use them, we propose a knowledge attention module, which learns to select and use informative knowledge based on contexts, to enhance our model. Experimental results on two datasets from different domains prove the validity and effectiveness of our model, where it outperforms state-of-the-art baselines by a large margin. Moreover, since our model learns to use external knowledge rather than only fitting the training data, it also demonstrates superior performance to baselines in the cross-domain setting.
* **keywords**:
* **interpretation**: [zhihu](https://zhuanlan.zhihu.com/p/85180047)
* **pdf**: [link](https://www.aclweb.org/anthology/P19-1083.pdf)
* **code**: [github](https://github.com/HKUST-KnowComp/Pronoun-Coref-KG)
* **dataset**: CoNLL, i2b2
* **ppt/video**:
* **curator**: Shuwei Yuan
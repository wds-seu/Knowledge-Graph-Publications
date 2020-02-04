# A Prism Module for Semantic Disentanglement in Name Entity Recognition

* **author**: Kun Liu, Shen Li, Daqi Zheng, Zhengdong Lu, Sheng Gao, Si Li
* **abstract**:Natural Language Processing has been perplexed for many years by the problem that multiple semantics are mixed inside a word, even with the help of context. To solve this problem, we propose a prism module to disentangle the semantic aspects of words and reduce noise at the input layer of a model. In the prism module, some words are selectively replaced with task-related semantic aspects, then these denoised word representations can be fed into downstream tasks to make them easier. Besides, we also introduce a structure to train this module jointly with the downstream model without additional data. This module can be easily integrated into the downstream model and significantly improve the performance of baselines on named entity recognition (NER) task. The ablation analysis demonstrates the rationality of the method. As a side effect, the proposed method also provides a way to visualize the contribution of each word.
* **keywords**:
* **interpretation**:
* **pdf**: [link](https://www.aclweb.org/anthology/P19-1532.pdf)
* **code**: [github](https://github.com/liukun95/Prism-Module)
* **dataset**:CoNLL 2003
* **ppt/video**:
* **curator**: Shuwei Yuan
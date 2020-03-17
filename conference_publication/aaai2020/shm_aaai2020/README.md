# Are Noisy Sentences Useless for Distant Supervised Relation Extraction?

* **author**:Yu-Ming Shang, He-Yan Huang, Xian-Ling Mao, Xin Sun, Wei Wei
* **abstract**:The noisy labeling problem has been one of the major obstacles for distant supervised relation extraction. Existing approaches usually consider that the noisy sentences are useless and will harm the model's performance. Therefore, they mainly alleviate this problem by reducing the influence of noisy sentences, such as applying bag-level selective attention or removing noisy sentences from sentence-bags. However, the underlying cause of the noisy labeling problem is not the lack of useful information, but the missing relation labels. Intuitively, if we can allocate credible labels for noisy sentences, they will be transformed into useful training data and benefit the model's performance. Thus, in this paper, we propose a novel method for distant supervised relation extraction, which employs unsupervised deep clustering to generate reliable labels for noisy sentences. Specifically, our model contains three modules: a sentence encoder, a noise detector and a label generator. The sentence encoder is used to obtain feature representations. The noise detector detects noisy sentences from sentence-bags, and the label generator produces high-confidence relation labels for noisy sentences. Extensive experimental results demonstrate that our model outperforms the state-of-the-art baselines on a popular benchmark dataset, and can indeed alleviate the noisy labeling problem.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1911.09788)
* **code**:NYT-10
* **ppt/video**:
* **curator**:Shuwei Yuan
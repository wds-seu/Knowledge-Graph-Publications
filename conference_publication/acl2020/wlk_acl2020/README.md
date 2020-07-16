#  Single-/Multi-Source Cross-Lingual NER via Teacher-Student Learning on Unlabeled Data in Target Language

* **author**: Qianhui Wu, Zijia Lin, Börje Karlsson, Jian-Guang LOU, Biqing Huang
* **abstract**:To better tackle the named entity recognition (NER) problem on languages with little/no labeled data, cross-lingual NER must effectively leverage knowledge learned from source languages with rich labeled data. Previous works on cross-lingual NER are mostly based on label projection with pairwise texts or direct model transfer. However, such methods either are not applicable if the labeled data in the source languages is unavailable, or do not leverage information contained in unlabeled data in the target language. In this paper, we propose a teacher-student learning method to address such limitations, where NER models in the source languages are used as teachers to train a student model on unlabeled data in the target language. The proposed method works for both single-source and multi-source cross-lingual NER. For the latter, we further propose a similarity measuring method to better weight the supervision from different teacher models. Extensive experiments for 3 target languages on benchmark datasets well demonstrate that our method outperforms existing state-of-the-art methods for both single-source and multi-source cross-lingual NER.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2004.12440)
* **code**:[github](https://github.com/microsoft/vert-papers/tree/3b41d7d73a3dd33ab648f5c26c9c0929aa79e7c3/papers/SingleMulti-TS)
* **dataset**:CoNLL-2002,CoNLL-2003
* **ppt/video**:
* **curator**:Shuwei Yuan
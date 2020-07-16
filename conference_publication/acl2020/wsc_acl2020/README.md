#  Pyramid: A Layered Model for Nested Named Entity Recognition

* **author**: Jue Wang, Lidan Shou, Ke Chen, Gang Chen
* **abstract**:This paper presents Pyramid, a novel layered model for Nested Named Entity Recognition (nested NER). In our approach, token or text region embeddings are recursively inputted into L flat NER layers, from bottom to top, stacked in a pyramid shape. Each time an embedding passes through a layer of the pyramid, its length is reduced by one. Its hidden state at layer l represents an l-gram in the input text, which is labeled only if its corresponding text region represents a complete entity mention. We also design an inverse pyramid to allow bidirectional interaction between layers. The proposed method achieves state-of-the-art F1 scores in nested NER on ACE-2004, ACE-2005, GENIA, and NNE, which are 80.27, 79.42, 77.78, and 93.70 with conventional embeddings, and 87.74, 86.34, 79.31, and 94.68 with pre-trained contextualized embeddings. In addition, our model can be used for the more general task of Overlapping Named Entity Recognition. A preliminary experiment confirms the effectiveness of our method in overlapping NER.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://www.aclweb.org/anthology/2020.acl-main.525.pdf)
* **code**:
* **dataset**: ACE-2004,ACE-2005,GENIA,NNE
* **ppt/video**:
* **curator**:Shuwei Yuan
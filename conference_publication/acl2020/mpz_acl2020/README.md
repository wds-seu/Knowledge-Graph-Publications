#  Simplify the Usage of Lexicon in Chinese NER

* **author**: Ruotian Ma, Minlong Peng, Qi Zhang, Zhongyu Wei, Xuanjing Huang
* **abstract**:Recently, many works have tried to utilizing word lexicon to augment the performance of Chinese named entity recognition (NER). As a representative work in this line, Lattice-LSTM \cite{zhang2018chinese} has achieved new state-of-the-art performance on several benchmark Chinese NER datasets. However, Lattice-LSTM suffers from a complicated model architecture, resulting in low computational efficiency. This will heavily limit its application in many industrial areas, which require real-time NER response. In this work, we ask the question: if we can simplify the usage of lexicon and, at the same time, achieve comparative performance with Lattice-LSTM for Chinese NER?
  Started with this question and motivated by the idea of Lattice-LSTM, we propose a concise but effective method to incorporate the lexicon information into the vector representations of characters. This way, our method can avoid introducing a complicated sequence modeling architecture to model the lexicon information. Instead, it only needs to subtly adjust the character representation layer of the neural sequence model. Experimental study on four benchmark Chinese NER datasets shows that our method can achieve much faster inference speed, comparative or better performance over Lattice-LSTM and its follwees. It also shows that our method can be easily transferred across difference neural architectures.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1908.05969)
* **code**:[github](https://link.zhihu.com/?target=https%3A//github.com/v-mipeng/LexiconAugmentedNER)
* **dataset**: OntoNotes,MSRA,Weibo,Resume
* **ppt/video**:
* **curator**:Shuwei Yuan
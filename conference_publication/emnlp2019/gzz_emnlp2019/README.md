# A Lexicon-Based Graph Neural Network for Chinese NER

- **author**:TaoGui, YichengZou, QiZhang, MinlongPeng, JinlanFu, ZhongyuWei, XuanjingHuang  
- **abstract**:Recurrent neural networks (RNN) used for Chinese named entity recognition (NER) that sequentially track character and word information have achieved great success. However, the characteristic of chain structure and the lack of global semantics determine that RNN-based models are vulnerable to word ambiguities. In this work, we try to alleviate this problem by introducing a lexicon-based graph neural network with global semantics, in which lexicon knowledge is used to connect characters to capture the local composition, while a global relay node can capture global sentence semantics and long-range dependency. Based on the multiple graph-based interactions among characters, potential words, and the whole-sentence semantics, word ambiguities can be effectively tackled. Experiments on four NER datasets show that the proposed model achieves significant improvements against other baseline models. 
- **keywords**:
- **interpretation**:待补充
- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1096.pdf )
- **code**: [code](https://github.com/RowitZou/LGN)
- **dataset**:OntoNotes 4.0,MSRA, Weibo NER,Resume NER
- **ppt/video**:
- **curator**: Yawen Dai
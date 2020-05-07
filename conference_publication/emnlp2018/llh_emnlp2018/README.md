## Leveraging Gloss Knowledge in Neural Word Sense Disambiguation by Hierarchical Co-Attention

**author**:Fuli Luo,Tianyu Liu1,Zexue He2,Qiaolin Xia,Zhifang Sui,Baobao Chang

**abstract**:The goal of Word Sense Disambiguation
(WSD) is to identify the correct meaning of a word in the particular context. Traditional supervised methods only use labeled data (context), while missing rich lexical knowledge such as the gloss which defines the meaning of a word sense. Recent studies have shown
that incorporating glosses into neural networks for WSD has made significant improvement. However, the previous models usually build the context representation and gloss representation separately. In this paper, we find that the learning for the context and gloss representation can benefit from each other. Gloss can help to highlight the important words in the context, thus building a better context representation. Context can also help to locate the key words in the gloss of the correct word sense. Therefore, we introduce a co-attention mechanism to generate co-dependent representations for the context and gloss. Furthermore, in order to capture both word-level and sentence-level information, we extend the attention mechanism in a hierarchical fashion. Experimental results show that our model achieves the state-of-the-art results on several standard English all-words WSD test datasets.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1170.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
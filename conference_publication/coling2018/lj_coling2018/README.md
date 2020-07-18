# Embedding WordNet Knowledge for Textual Entailment
* **author**: Yunshi Lan, Jing Jiang
* **abstract**: In this paper, we study how we can improve a deep learning approach to textual entailment by incorporating lexical entailment relations from WordNet. Our idea is to embed the lexical entailment knowledge contained in WordNet in specially-learned word vectors, which we call “entailment vectors.” We present a standard neural network model and a novel set-theoretic model to learn these entailment vectors from word pairs with known lexical entailment relations derived from WordNet. We further incorporate these entailment vectors into a decomposable attention model for textual entailment and evaluate the model on the SICK and the SNLI dataset. We find that using these special entailment word vectors, we can significantly improve the performance of textual entailment compared with a baseline that uses only standard word2vec vectors. The final performance of our model is close to or above the state of the art, but our method does not rely on any manually-crafted rules or extensive syntactic features.
* **keywords**: entailment vectors, textual entailment
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.aclweb.org/anthology/C18-1023.pdf)
* **code**: [link](https://github.com/lanyunshi/embedding-for-textual-entailment)
* **dataset**: SICK, SNLI
* **ppt/video**:
* **curation**: Jiong Zhang 
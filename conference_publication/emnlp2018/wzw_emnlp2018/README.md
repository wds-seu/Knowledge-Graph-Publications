## Label-Free Distant Supervision for Relation Extraction via Knowledge Graph Embedding

**author**:Guanying Wang, Wen Zhang, Ruoxu Wang, Yalin Zhou， Xi Chen, Wei Zhang, Hai Zhu, and Huajun Chen

**abstract**:Distant supervision is an effective method to generate large scale labeled data for relation
extraction, which assumes that if a pair of entities appears in some relation of a Knowledge Graph (KG), all sentences containing those entities in a large unlabeled corpus are then labeled with that relation to train a relation classifier. However, when the pair of entities has multiple relationships in the KG, this assumption may produce noisy relation labels. This
paper proposes a label-free distant supervision
method, which makes no use of the relation labels under this inadequate assumption, but only uses the prior knowledge derived from the KG to supervise the learning of the classifier directly and softly. Specifically, we make use of the type information and the translation law derived from typical KG embedding model to learn embeddings for certain sentence patterns. As the supervision signal is only determined by the two aligned entities, neither hard relation labels nor extra noise-reduction model for the bag of sentences is needed in this way. The experiments show that the approach performs well in current distant supervision dataset.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1248.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
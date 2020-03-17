# Contextual Parameter Generation for Knowledge Graph Link Prediction

* **author**:George Stoica, Otilia Stretcu, Emmanouil Antonios Platanio, Tom M. Mitchell,Barnabas Poczos
* **abstract**:Knowledge graph link prediction is the task of inferring missing relationships between entities in a knowledge graph. It can be seen as a form of question answering, where given a question consisting of an entity and a relation (e.g., “Shakespeare” and “bornIn”), we are tasked with predicting the most likely answer entity (e.g., “England”). Recent methods have focused on inferring answers by learning entity and relation embeddings. For example, the current state-of-the-art, ConvE, stacks the question entity and relation embeddings together and uses a convolutional neural network to predict the answer entity. However, we argue that entities and relations model different kinds of information and thus, integrating them in this way does not represent a meaningful inductive bias for the model. Therefore, we instead propose to treat relations as the “context” in which question entities are interpreted and transformed to produce answer entities. Concretely, we use relation embeddings to generate the parameters of a model operating over entity embeddings, which in turn produces a distribution over possible answers. This proposed model outperforms all existing methods by a significant margin on several established datasets, thus establishing the new state-of-the-art for this problem, while at the same time reducing training time by up to 98%.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://platanios.org/assets/pdf/platanios_2020_coper/paper.pdf)
* **code**:[github](https://github.com/otiliastr/coper)
* **dataset**:UMLS,Kinship,WN18RR,FB15k237,NELL-995
* **ppt/video**:
* **curator**:Shuwei Yuan
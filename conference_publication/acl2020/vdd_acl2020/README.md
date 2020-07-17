# Exploiting the Syntax-Model Consistency for Neural Relation Extraction

* **author**: Amir Pouran Ben Veyseh, Franck Dernoncourt, Dejing Dou, Thien Huu Nguyen
* **abstract**:This paper studies the task of Relation Extraction (RE) that aims to identify the semantic relations between two entity mentions in text. In the deep learning models for RE, it has been beneficial to incorporate the syntactic structures from the dependency trees of the input sentences. In such models, the dependency trees are often used to directly structure the network architectures or to obtain the dependency relations between the word pairs to inject the syntactic information into the models via multi-task learning. The major problem with these approaches is the lack of generalization beyond the syntactic structures in the training data or the failure to capture the syntactic importance of the words for RE. In order to overcome these issues, we propose a novel deep learning model for RE that uses the dependency trees to extract the syntax-based importance scores for the words, serving as a tree representation to introduce syntactic information into the models with greater generalization. In particular, we leverage Ordered-Neuron Long-Short Term Memory Networks (ON-LSTM) to infer the model-based importance scores for RE for every word in the sentences that are then regulated to be consistent with the syntax-based scores to enable syntactic information injection. We perform extensive experiments to demonstrate the effectiveness of the proposed method, leading to the state-of-the-art performance on three RE benchmark datasets.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://www.aclweb.org/anthology/2020.acl-main.715.pdf)
* **code**:
* **dataset**:ACE2005,SPOUSE,SciERC
* **ppt/video**:
* **curator**:Shuwei Yuan


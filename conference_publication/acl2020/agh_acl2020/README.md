# Probing Linguistic Features of Sentence-Level Representations in Neural Relation Extraction

* **author**: Christoph Alt, Aleksandra Gabryszak, Leonhard Hennig
* **abstract**:Despite the recent progress, little is known about the features captured by state-of-the-art neural relation extraction (RE) models. Common methods encode the source sentence, conditioned on the entity mentions, before classifying the relation. However, the complexity of the task makes it difficult to understand how encoder architecture and supporting linguistic knowledge affect the features learned by the encoder. We introduce 14 probing tasks targeting linguistic properties relevant to RE, and we use them to study representations learned by more than 40 different encoder architecture and linguistic feature combinations trained on two datasets, TACRED and SemEval 2010 Task 8. We find that the bias induced by the architecture and the inclusion of linguistic features are clearly expressed in the probing task performance. For example, adding contextualized word representations greatly increases performance on probing tasks with a focus on named entity and part-of-speech information, and yields better results in RE. In contrast, entity masking improves RE, but considerably lowers performance on entity type related probing tasks.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2004.08134)
* **code**:[github](https://github.com/DFKI-NLP/REval)
* **dataset**:SemEval,TACRED
* **ppt/video**:
* **curator**:Shuwei Yuan


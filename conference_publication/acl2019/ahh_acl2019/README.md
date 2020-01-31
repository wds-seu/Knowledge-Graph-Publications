# Fine-tuning Pre-Trained Transformer Language Models to Distantly Supervised Relation Extraction

* **author**: Christoph Alt, Marc Hübner, Leonhard Hennig
* **abstract**: Distantly supervised relation extraction is widely used to extract relational facts from text, but suffers from noisy labels. Current relation extraction methods try to alleviate the noise by multi-instance learning and by providing supporting linguistic and contextual information to more efficiently guide the relation classification. While achieving state-of-the-art results, we observed these models to be biased towards recognizing a limited set of relations with high precision, while ignoring those in the long tail. To address this gap, we utilize a pre-trained language model, the OpenAI Generative Pre-trained Transformer (GPT) (Radford et al., 2018). The GPT and similar models have been shown to capture semantic and syntactic features, and also a notable amount of “common-sense” knowledge, which we hypothesize are important features for recognizing a more diverse set of relations. By extending the GPT to the distantly supervised setting, and fine-tuning it on the NYT10 dataset, we show that it predicts a larger set of distinct relation types with high confidence. Manual and automated evaluation of our model shows that it achieves a state-of-the-art AUC score of 0.422 on the NYT10 dataset, and performs especially well at higher recall levels.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://www.aclweb.org/anthology/P19-1134.pdf)
* **code**: [github](https://github.com/DFKI-NLP/DISTRE)
* **dataset**: NYT10
* **ppt/video**:
* **curator**: Shuwei Yuan
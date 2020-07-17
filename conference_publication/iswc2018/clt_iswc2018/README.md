# A Novel Ensemble Method for Named Entity Recognition and Disambiguation Based on Neural Network
* **author**：Lorenzo Canale，Pasquale Lisena，Rapha¨el Troncy
* **abstract**: Named entity recognition (NER) and disambiguation (NED) are subtasks of information extraction that aim to recognize named entities mentioned in text, to assign them pre-defined types, and to link them with their matching entities in a knowledge base. Many approaches, often exposed as web APIs, have been proposed to solve these tasks during the last years. These APIs classify entities using different taxonomies and disambiguate them with different knowledge bases. In this paper, we describe Ensemble Nerd, a framework that collects numerous extractors responses, normalizes them and combines them in order to produce a final entity list according to the pattern (surface form, type, link). The presented approach is based on representing the extractors responses as real-value vectors and on using them as input samples for two Deep Learning networks: ENNTR (Ensemble Neural Network for Type Recognition) and ENND (Ensemble Neural Network for Disambiguation). We train these networks using specific gold standards. We show that the models produced outperform each single extractor responses in terms of micro and macro F1 measures computed by the GERBIL framework.
* **keywords**: Ensemble Methods, Neural Network, Ensembles Extract Responses, Type Recognition, Single Infusion 
* **interpretation**: 
* **pdf**:  [link](http://www.eurecom.fr/en/publication/5564/download/data-publi-5564.pdf)
* **code**: [link](https://github.com/D2KLab/ensemble-nerd)
* **dataset**: OKE2016, AIDA/CoNLL, NexGenTV
* **ppt/video**: 
* **curator**: Chang Liu

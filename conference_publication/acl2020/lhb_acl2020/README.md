# Named Entity Recognition without Labelled Data: A Weak Supervision Approach

* **author**: Pierre Lison, Aliaksandr Hubin, Jeremy Barnes, Samia Touileb
* **abstract**: Named Entity Recognition (NER) performance often degrades rapidly when applied to target domains that differ from the texts observed during training. When in-domain labelled data is available, transfer learning techniques can be used to adapt existing NER models to the target domain. But what should one do when there is no hand-labelled data for the target domain? This paper presents a simple but powerful approach to learn NER models in the absence of labelled data through weak supervision. The approach relies on a broad spectrum of labelling functions to automatically annotate texts from the target domain. These annotations are then merged together using a hidden Markov model which captures the varying accuracies and confusions of the labelling functions. A sequence labelling model can finally be trained on the basis of this unified annotation. We evaluate the approach on two English datasets (CoNLL 2003 and news articles from Reuters and Bloomberg) and demonstrate an improvement of about 7 percentage points in entity-level F1 scores compared to an out-of-domain neural NER model.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2004.14723)
* **code**:
* **dataset**: CoNLL 2003，Reuters&Bloomberg
* **ppt/video**:
* **curator**:Shuwei Yuan
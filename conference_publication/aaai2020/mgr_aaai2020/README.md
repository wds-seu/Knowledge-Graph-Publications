# Robust Named Entity Recognition with Truecasing Pretraining

* **author**:Stephen Mayhew, Nitish Gupta, Dan Roth
* **abstract**:Although modern named entity recognition (NER) systems show impressive performance on standard datasets, they perform poorly when presented with noisy data. In particular, capitalization is a strong signal for entities in many languages, and even state of the art models overfit to this feature, with drastically lower performance on uncapitalized text. In this work, we address the problem of robustness of NER systems in data with noisy or uncertain casing, using a pretraining objective that predicts casing in text, or a truecaser, leveraging unlabeled data. The pretrained truecaser is combined with a standard BiLSTM-CRF model for NER by appending output distributions to character embeddings. In experiments over several datasets of varying domain and casing quality, we show that our new model improves performance in uncased text, even adding value to uncased BERT embeddings. Our method achieves a new state of the art on the WNUT17 shared task dataset.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1912.07095)
* **code**:
* **dataset**:CoNLL2003,Ontonotes v5,WNUT17
* **ppt/video**:
* **curator**:Shuwei Yuan
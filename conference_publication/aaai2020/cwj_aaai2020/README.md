# Improving Entity Linking by Modeling Latent Entity Type Information

* **author**: Shuang Chen, Jinpeng Wang, Feng Jiang, Chin-Yew Lin
* **abstract**:Existing state of the art neural entity linking models employ attention-based bag-of-words context model and pre-trained entity embeddings bootstrapped from word embeddings to assess topic level context compatibility. However, the latent entity type information in the immediate context of the mention is neglected, which causes the models often link mentions to incorrect entities with incorrect type. To tackle this problem, we propose to inject latent entity type information into the entity embeddings based on pre-trained BERT. In addition, we integrate a BERT-based entity similarity score into the local context model of a state-of-the-art model to better capture latent entity type information. Our model significantly outperforms the state-of-the-art entity linking models on standard benchmark (AIDA-CoNLL). Detailed experiment analysis demonstrates that our model corrects most of the type errors produced by the direct baseline.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2001.01447)
* **code**: 
* **dataset**:AIDA-CoNLL,MSNBC,AQUAINT,ACE2004,CWEB,WIKI
* **ppt/video**:
* **curator**:Shuwei Yuan
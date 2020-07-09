# Co-training Embeddings of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment
* **author**：Muhao Chen, Yingtao Tian, Kai-Wei Chang, Steven Skiena, Carlo Zaniolo
* **abstract**: Multilingual knowledge graph (KG) embeddings provide latent semantic representations of entities and structured knowledge with cross-lingual inferences, which benefit various knowledge-driven cross-lingual NLP tasks. However, precisely learning such cross-lingual inferences is usually hindered by the low coverage of entity alignment in many KGs. Since many multilingual KGs also provide literal descriptions of entities, in this paper, we introduce an embedding-based approach which leverages a weakly aligned multilingual KG for semi-supervised cross-lingual learning using entity descriptions. Our approach performs co-training of two embedding models, i.e. a multilingual KG embedding model and a multilingual literal description embedding model. The models are trained on a large Wikipedia-based trilingual dataset where most entity alignment is unknown to training. Experimental results show that the performance of the proposed approach on the entity alignment task improves at each iteration of co-training, and eventually reaches a stage at which it significantly surpasses previous approaches. We also show that our approach has promising abilities for zero-shot entity alignment, and cross-lingual KG completion.
* **keywords**: Machine Learning: Relational Learning, Machine Learning: Semi-Supervised Learning, Machine Learning: Knowledge-based Learning, Natural Language Processing: Embeddings
* **interpretation**: 
* **pdf**:  [link](https://www.ijcai.org/Proceedings/2018/0556.pdf)
* **code**: 
* **dataset**: WK3l60k,
* **ppt/video**: 
* **curator**: Chang Liu

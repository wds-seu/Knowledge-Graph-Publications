# Neural Relation Extraction for Knowledge Base Enrichment

* **author**：Bayu Distiawan Trisedya, Gerhard Weikum, Jianzhong Qi, Rui Zhang
* **abstract**:We study relation extraction for knowledge base (KB) enrichment. Specifically, we aim to extract entities and their relationships from sentences in the form of triples and map the elements of the extracted triples to an existing KB in an end-to-end manner. Previous studies focus on the extraction itself and rely on Named Entity Disambiguation (NED) to map triples into the KB space. This way, NED errors may cause extraction errors that affect the overall precision and recall.To address this problem, we propose an end-to-end relation extraction model for KB enrichment based on a neural encoder-decoder model. We collect high-quality training data by distant supervision with co-reference resolution and paraphrase detection. We propose an n-gram based attention model that captures multi-word entity names in a sentence. Our model employs jointly learned word and entity embeddings to support named entity disambiguation. Finally, our model uses a modified beam search and a triple classifier to help generate high-quality triples. Our model outperforms state-of-the-art baselines by 15.51% and 8.38% in terms of F1 score on two real-world datasets.
* **keywords**:
* **interpretation**:
* **pdf**: [link](https://www.aclweb.org/anthology/P19-1023.pdf)
* **code**:
* **dataset**: WIKI,GEO
* **ppt/video**:
* **curator**:Shuwei Yuan
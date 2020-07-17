# Reasoning with Latent Structure Refinement for Document-Level Relation Extraction

* **author**: Guoshun Nan, Zhijiang Guo, Ivan Sekulic, Wei Lu
* **abstract**:Document-level relation extraction requires integrating information within and across multiple sentences of a document and capturing complex interactions between inter-sentence entities. However, effective aggregation of relevant information in the document remains a challenging research question. Existing approaches construct static document-level graphs based on syntactic trees, co-references or heuristics from the unstructured text to model the dependencies. Unlike previous methods that may not be able to capture rich non-local interactions for inference, we propose a novel model that empowers the relational reasoning across sentences by automatically inducing the latent document-level graph. We further develop a refinement strategy, which enables the model to incrementally aggregate relevant information for multi-hop reasoning. Specifically, our model achieves an F1 score of 59.05 on a large-scale document-level dataset (DocRED), significantly improving over the previous results, and also yields new state-of-the-art results on the CDR and GDA dataset. Furthermore, extensive analyses show that the model is able to discover more accurate inter-sentence relations.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2005.06312)
* **code**:[github](https://github.com/nanguoshun/LSR)
* **dataset**:DocRED
* **ppt/video**:
* **curator**:Shuwei Yuan


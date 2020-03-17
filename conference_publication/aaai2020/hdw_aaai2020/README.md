# Leveraging Multi-­‐token Entities in Document-­‐level Named Entity Recognition

* **author**: Anwen Hu , Zhicheng Dou , Ji-­‐Rong Wen,Jian-­‐Yun Nie
* **abstract**:Most state-of-the-art named entity recognition systems are designed to process each sentence within a document independently. These systems are easy to confuse entity types
  when the context information in a sentence is not sufficient enough. To utilize the context information within the whole document, most document-level work let neural networks on their own to learn the relation across sentences, which is not intuitive enough for us humans. In this paper, we divide entities
  to multi-token entities that contain multiple tokens and single-token entities that are composed of a single token. We propose that the context information of multi-token entities should be more reliable in document-level NER for news articles. We design a fusion attention mechanism which not only learns the semantic relevance between occurrences of the same token, but also focuses more on occurrences belonging to multi-tokens entities. To identify multi-token entities, we design an auxiliary task namely ‘Multi-token Entity Classification’ and perform this task simultaneously with document-level NER. This auxiliary task is simplified from NER and doesn’t require extra annotation. Experimental results on the CoNLL-2003 dataset and OntoNotesnbm dataset show that our model outperforms state-of-the-art sentencelevel and document-level NER methods.
* **keywords**:
* **interpretation**:
* **pdf**:[link](http://playbigdata.ruc.edu.cn/dou/publication/2020_aaai_ner.pdf)
* **code**:
* **dataset**: CoNLL-2003,OntoNotes(nbm)
* **ppt/video**:
* **curator**:Shuwei Yuan
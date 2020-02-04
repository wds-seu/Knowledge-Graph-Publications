# Barack’s Wife Hillary: Using Knowledge Graphs for Fact-Aware Language Modeling

* **author**: Robert Logan, Nelson F. Liu, Matthew E. Peters, Matt Gardner, Sameer Singh
* **abstract**: Modeling human language requires the ability to not only generate fluent text but also encode factual knowledge. However, traditional language models are only capable of remembering facts seen at training time, and often have difficulty recalling them. To address this, we introduce the knowledge graph language model (KGLM), a neural language model with mechanisms for selecting and copying facts from a knowledge graph that are relevant to the context. These mechanisms enable the model to render information it has never seen before, as well as generate out-of-vocabulary tokens. We also introduce the Linked WikiText-2 dataset, a corpus of annotated text aligned to the Wikidata knowledge graph whose contents (roughly) match the popular WikiText-2 benchmark. In experiments, we demonstrate that the KGLM achieves significantly better performance than a strong baseline language model. We additionally compare different language model’s ability to complete sentences requiring factual knowledge, showing that the KGLM outperforms even very large language models in generating facts.
* **keywords**:
* **interpretation**: 
* **pdf**: [link](https://www.aclweb.org/anthology/P19-1598.pdf)
* **code**: [github](https://github.com/rloganiv/kglm-model)
* **dataset**: Linked WikiText-2
* **ppt/video**: 
* **curator**:Shuwei Yuan
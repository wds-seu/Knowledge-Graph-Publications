# Hierarchical Losses and New Resources for Fine-grained Entity Typing and Linking
* **author**：Shikhar Murty, Patrick Verga, Luke Vilnis, Irena Radovanovic, Andrew McCallum
* **abstract**: Extraction from raw text to a knowledge base of entities and fine-grained types is often cast as prediction into a flat set of entity and type labels, neglecting the rich hierarchies over types and entities contained in curated ontologies. Previous attempts to incorporate hierarchical structure have yielded little benefit and are restricted to shallow ontologies. This paper presents new methods using real and complex bilinear mappings for integrating hierarchical information, yielding substantial improvement over flat predictions in entity linking and fine-grained entity typing, and achieving new state-of-the-art results for end-to-end models on the benchmark FIGER dataset. We also present two new human-annotated datasets containing wide and deep hierarchies which we will release to the community to encourage further research in this direction: MedMentions, a collection of PubMed abstracts in which 246k mentions have been mapped to the massive UMLS ontology; and TypeNet, which aligns Freebase types with the WordNet hierarchy to obtain nearly 2k entity types. In experiments on all three datasets we show substantial gains from hierarchy-aware training.
* **keywords**: 
* **interpretation**: [link](https://www.jianshu.com/p/ad4799873afb)
* **pdf**:  [link](https://www.aclweb.org/anthology/P18-1010.pdf)
* **code**: [link](https://github.com/MurtyShikhar/Hierarchical-Typing)
* **dataset**: FIGER, Wikipedia, MedMentions
* **ppt/video**: 
* **curator**: Chang Liu

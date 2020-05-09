# OpenKI: Integrating Open Information Extraction and Knowledge Bases with Relation Inference
* **author**: Dongxu Zhang, Subhabrata Mukherjee, Colin Lockard, Luna Dong, Andrew McCallum
* **abstract**: In this paper, we consider advancing web-scale knowledge extraction and alignment by integrating OpenIE extractions in the form of (subject, predicate, object) triples with Knowledge Bases (KB). Traditional techniques from universal schema and from schema mapping fall in two extremes: either they perform instance-level inference relying on embedding for (subject, object) pairs, thus cannot handle pairs absent in any existing triples; or they perform predicate-level mapping and completely ignore background evidence from individual entities, thus cannot achieve satisfying quality. We propose *OpenKI* to handle sparsity of OpenIE extractions by performing instance-level inference: for each entity, we encode the rich information in its neighborhood in both KB and OpenIE extractions, and leverage this information in relation inference by exploring different methods of aggregation and attention. In order to handle unseen entities, our model is designed without creating entity-specific parameters. Extensive experiments show that this method not only significantly improves state-of-the-art for conventional OpenIE extractions like ReVerb, but also boosts the performance on OpenIE from semi-structured data, where new entity pairs are abundant and data are fairly sparse.
* **keywords**: 
* **interpretation**: 
* **pdf**: [paper](https://www.aclweb.org/anthology/N19-1083.pdf)
* **code**: 
* **dataset**: Ceres, ReVerb, Freebase [dataset in github](https://github.com/zhangdongxu/relation-inference-naacl19)
* **ppt/video**:
* **curation**: Xiaoyu Shang

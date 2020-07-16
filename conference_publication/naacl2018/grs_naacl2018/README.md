# Joint Bootstrapping Machines for High Confidence Relation Extraction
* **author**: Pankaj Gupta, Benjamin Roth, Hinrich Schütze
* **abstract**: Semi-supervised bootstrapping techniques for relationship extraction from text iteratively expand a set of initial seed instances. Due to the lack of labeled data, a key challenge in bootstrapping is semantic drift: if a false positive instance is added during an iteration, then all following iterations are contaminated. We introduce BREX, a new bootstrapping method that protects against such contamination by highly effective confidence assessment. This is achieved by using entity and template seeds jointly (as opposed to just one as in previous work), by expanding entities and templates in parallel and in a mutually constraining fashion in each iteration and by introducing higherquality similarity measures for templates. Experimental results show that BREX achieves an F1 that is 0.13 (0.87 vs. 0.74) better than the state of the art for four relationships.
* **keywords**: 
* **interpretation**: 
* **pdf**: [paper](https://www.aclweb.org/anthology/N18-1003.pdf)
* **code**: [github](https://github.com/pgcool/Joint-Bootstrapping-Machines)
* **dataset**: BREE 
* **ppt/video**: [video](http://vimeo.com/276391396)
* **curation**: Xiaoyu Shang

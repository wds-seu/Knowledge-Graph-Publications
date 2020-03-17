# CaRe Open Knowledge Graph Embeddings

- **author**:  Swapnil Gupta, Sreyash Kenkre, Partha Talukdar

- **abstract**: Open Information Extraction (OpenIE) methods are effective at extracting (noun phrase, relation phrase, noun phrase) triples from text, e.g., (Barack Obama, took birth in, Honolulu). Organization of such triples in the form of a graph with noun phrases (NPs) as nodes and relation phrases (RPs) as edges results in the construction of Open Knowledge Graphs (OpenKGs). In order to use such OpenKGs in downstream tasks, it is often desirable to learn embeddings of the NPs and RPs present in the graph. Even though several Knowledge Graph (KG) embedding methods have been recently proposed, all of those methods have targeted Ontological KGs, as opposed to OpenKGs. Straightforward application of existing Ontological KG embedding methods to OpenKGs is challenging, as unlike Ontological KGs, OpenKGs are not canonicalized, i.e., a real-world entity may be represented using multiple nodes in the OpenKG, with each node corresponding to a different NP referring to the entity. For example, nodes with labels Barack Obama, Obama, and President Obama may refer to the same real-world entity Barack Obama. Even though canonicalization of OpenKGs has received some attention lately, output of such methods has not been used to improve OpenKG embed- dings. We fill this gap in the paper and propose Canonicalization-infused Representations (CaRe) for OpenKGs. Through extensive experiments, we observe that CaRe enables existing models to adapt to the challenges in OpenKGs and achieve substantial improvements for the link prediction task. 

- **keywords**:

- **interpretation**:待补充

- **pdf**: [pdf](https://www.aclweb.org/anthology/D19-1036.pdf)

- **code**: [code](https://github.com/malllabiisc/CaRE)

- **dataset**: ReVerb45K,ReVerb20K

- **ppt/video**:

- **curator**: Yawen Dai
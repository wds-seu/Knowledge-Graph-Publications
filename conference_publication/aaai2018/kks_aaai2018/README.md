# Question Answering as Global Reasoning Over Semantic Abstractions
* **author**: Daniel Khashabi, Tushar Khot, Ashish Sabharwal, Dan Roth
* **abstract**: We propose a novel method for exploiting the semantic structure of text to answer multiple-choice questions. The approach is especially suitable for domains that require reasoning over a diverse set of linguistic constructs but have limited training data. To address these challenges, we present the first system, to the best of our knowledge, that reasons over a wide range of semantic abstractions of the text, which are derived using off-the-shelf, general-purpose, pre-trained natural language modules such as semantic role labelers, coreference resolvers, and dependency parsers. Representing multiple abstractions as a family of graphs, we translate question answering (QA) into a search for an optimal subgraph that satisfies certain global and local properties. This formulation generalizes several prior structured QA systems. Our system, SEMANTICILP, demonstrates strong performance on two domains simultaneously. In particular, on a collection of challenging science QA datasets, it outperforms various state-of-the-art approaches, including neural models, broad coverage information retrieval, and specialized techniques using structured
* **keywords**: global reason, QA
* **interpretation**: [来源: 知乎](https://zhuanlan.zhihu.com/p/35721485)
* **pdf**: [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17406/15895)
* **code**: [link](https://github.com/allenai/semanticilp)
* **dataset**: REGENTS 4TH, REGENTS 8TH, AI2PUBLIC 4TH , AI2PUBLIC 8TH, PROCESSBANK
* **ppt/video**:
* **curation**: Jiong Zhang 
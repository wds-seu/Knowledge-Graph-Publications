# PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text

- **author**:Haitian Sun Tania Bedrax-Weiss William W.Cohen 

- **abstract**: We consider open-domain queston answering (QA) where answers are drawn from either a corpus, a knowledge base (KB), or a combination of both of these. We focus on a setting in which a corpus is supplemented with a large but incomplete KB, and on questions that require non-trivial (e.g., multi-hop) reasoning. We describe PullNet, an integrated framework for (1) learning what to retrieve (from the KB and/or corpus) and (2) reasoning with this heterogeneous information to find the best answer. PullNet uses an {iterative} process to construct a question-specific subgraph that contains information relevant to the question. In each iteration, a graph convolutional network (graph CNN) is used to identify subgraph nodes that should be expanded using retrieval (or ``pull'') operations on the corpus and/or KB. After the subgraph is complete, a similar graph CNN is used to extract the answer from the subgraph. This retrieve-and-reason process allows us to answer multi-hop questions using large KBs and corpora. PullNet is weakly supervised, requiring question-answer pairs but not gold inference paths. Experimentally PullNet improves over the prior state-of-the art, and in the setting where a corpus is used with incomplete KB these improvements are often dramatic. PullNet is also often superior to prior systems in a KB-only setting or a text-only setting.  

- **keywords**:

- **interpretation**: [review](https://www.jianshu.com/p/7b33d77c108b)

- **pdf**: [pdf](https://arxiv.org/pdf/1904.09537)

- **code**: 

- **dataset**: MetaQA

- **ppt/video**:

- **curator**: Yawen Dai

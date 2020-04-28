# Learning to Transform, Combine, and Reason in Open-Domain Question Answering
* **author**: Mostafa Dehghani, Hosein Azarbonyad, Jaap Kamps, Maarten de Rijke
* **abstract**: Users seek direct answers to complex questions from large open-domain knowledge sources like the Web. Open-domain question answering has become a critical task to be solved for building systems that help address users' complex information needs. Most open-domain question answering systems use a search engine to retrieve a set of candidate documents, select one or a few of them as context, and then apply reading comprehension models to extract answers. Some questions, however, require taking a broader context into account, e.g., by considering low-ranked documents that are not immediately relevant, combining information from multiple documents, and reasoning over multiple facts from these documents to infer the answer. In this paper, we propose a model based on the Transformer architecture that is able to efficiently operate over a larger set of candidate documents by effectively combining the evidence from these documents during multiple steps of reasoning, while it is robust against noise from low-ranked non-relevant documents included in the set. We use our proposed model, called TraCRNet, on two public open-domain question answering datasets, SearchQA and Quasar-T, and achieve results that meet or exceed the state-of-the-art.
* **keywords**: combine information from multiple documents, question answer
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://dl.acm.org/doi/pdf/10.1145/3289600.3291012?download=true)
* **code**: [link](https://github.com/MostafaDehghani/TraCRNet)
* **dataset**: SearchQA, Quasar-T
* **ppt/video**:
* **curation**: Jiong Zhang 
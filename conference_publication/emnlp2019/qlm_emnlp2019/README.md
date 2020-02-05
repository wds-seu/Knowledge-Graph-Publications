# Answering Complex Open-domain Questions Through Iterative Query Generation

- **author**:Peng Qi,Xiaowen Lin, Leo Mehr,Zijian Wang, Christopher D. Manning
- **abstract**: It is challenging for current one-step retrieve-and-read question answering (QA) systems to answer questions like "Which novel by the author of 'Armada' will be adapted as a feature film by Steven Spielberg?" because the question seldom contains retrievable clues about the missing entity (here, the author). Answering such a question requires multi-hop reasoning where one must gather information about the missing entity (or facts) to proceed with further reasoning. We present GoldEn (Gold Entity) Retriever, which iterates between reading context and retrieving more supporting documents to answer open-domain multi-hop questions. Instead of using opaque and computationally expensive neural retrieval models, GoldEn Retriever generates natural language search queries given the question and available context, and leverages off-the-shelf information retrieval systems to query for missing entities. This allows GoldEn Retriever to scale up efficiently for open-domain multi-hop reasoning while maintaining interpretability. We evaluate GoldEn Retriever on the recently proposed open-domain multi-hop QA dataset, HotpotQA, and demonstrate that it outperforms the best previously published model despite not using pretrained language models such as BERT. 
- **keywords**:
- **interpretation**:[review](http://mini.eastday.com/mobile/191108220422841.html#)
- **pdf**: [pdf](https://arxiv.org/pdf/1910.07000v1)
- **code**: [code](https://github.com/qipeng/golden-retriever)
- **dataset**: HOTPOTQA,
- **ppt/video**:
- **curator**: Yawen Dai
# Entity-Consistent End-to-end Task-Oriented Dialogue System with KB Retriever

- **author**:Libo Qin,Yijia Liu,Wanxiang Che,Haoyang Wen,Yangming Li,Ting Liu 

- **abstract**: Querying the knowledge base (KB) has long been a challenge in the end-to-end task-oriented dialogue system. Previous sequence-to-sequence (Seq2Seq) dialogue generation work treats the KB query as an attention over the entire KB, without the guarantee that the generated entities are consistent with each other. In this paper, we propose a novel framework which queries the KB in two steps to improve the consistency of generated entities. In the first step, inspired by the observation that a response can usually be supported by a single KB row, we introduce a KB retrieval component which explicitly returns the most relevant KB row given a dialogue history. The retrieval result is further used to filter the irrelevant entities in a Seq2Seq response generation model to improve the consistency among the output entities. In the second step, we further perform the attention mechanism to address the most correlated KB column. Two methods are proposed to make the training feasible without labeled retrieval data, which include distant supervision and Gumbel-Softmax technique. Experiments on two publicly available task oriented dialog datasets show the effectiveness of our model by outperforming the baseline systems and producing entity-consistent responses. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1909.06762)

- **code**: [code](https://github.com/yizhen20133868/Retriever-Dialogue)

- **dataset**: Camrest, InCar Assistant 

- **ppt/video**:

- **curator**: Yawen Dai
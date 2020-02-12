# Incorporating Graph Attention Mechanism into Knowledge Graph Reasoning Based on Deep Reinforcement Learning

- **author**:Heng Wang, Shuangyin Li, Rong Pan, Mingzhi Mao

- **abstract**: Knowledge Graph (KG) reasoning aims at finding reasoning paths for relations, in order to solve the problem of incompleteness in KG. Many previous path-based methods like PRA and DeepPath suffer from lacking memory components, or stuck in training. Therefore, their performances always rely on well-pretraining. In this paper, we present a deep reinforcement learning based model named by AttnPath, which incorporates LSTM and Graph Attention Mechanism as the memory components. We define two metrics, Mean Selection Rate (MSR) and Mean Replacement Rate (MRR), to quantitatively measure how difficult it is to learn the query relations, and take advantages of them to fine-tune the model under the framework of reinforcement learning. Meanwhile, a novel mechanism of reinforcement learning is proposed by forcing an agent to walk forward every step to avoid the agent stalling at the same entity node constantly. Based on this operation, the proposed model not only can get rid of the pretraining process, but also achieves state-of-the-art performance comparing with the other models. We test our model on FB15K-237 and NELL-995 datasets with different tasks. Extensive experiments show that our model is effective and competitive with many current state-of-the-art methods, and also performs well in practice. 

- **keywords**:

- **interpretation**:[review](https://zhuanlan.zhihu.com/p/98555596)

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1264.pdf )

- **code**: 

- **dataset**: FB15K-237 ,NELL-995

- **ppt/video**:

- **curator**: Yawen Dai
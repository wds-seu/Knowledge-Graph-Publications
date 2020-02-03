# Knowledge Graph Grounded Goal Planning for Open-­‐Domain Conversation Generation

* **author**: Jun Xu,Haifeng Wang,Zhengyu Niu,Hua Wu,Wanxiang Che
* **abstract**: Previous neural models on open-domain conversation generation have no effective mechanisms to manage chatting topics, and tend to produce less coherent dialogs.Inspired by the strategies in human-human dialogs,we divide the task of multi-turn open-domain conversation generation into two sub-tasks:explicit goal(chatting about a topic)sequence planning and goal completion by topic elaboration.To this end,we propose a three-layer Knowledge aware Hierarchical Reinforcement Learning based Model(KnowHRL).Specifically, for the first sub-task,the upper-layer policy learns to traverse a knowledge graph(KG)in order to plan a high-level goal sequence towards a good balance between dialog coherence and topic consistency with user interests.For the second sub-task,the middle-layer policy and the lower-layer one work together to produce an in-depth multi-turn conversation about a single topic with a goal-driven generation mechanism. The capability of goal-sequence planning enables chatbots to conduct proactive open-domain conversations towards recommended topics,which has many practical applications. Experiments demonstrate that our model outperforms state of the art baselines in terms of user-interest consistency,dialog coherence,and knowledge accuracy.
* **keywords**:
* **interpretation**: 
* **pdf**: [link](http://ir.hit.edu.cn/~car/papers/AAAI2020-Xu-kg.pdf)
* **code**:
* **dataset**:DuConv
* **ppt/video**:
* **curator**:Shuwei Yuan
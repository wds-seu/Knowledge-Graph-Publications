## Modelling Domain Relationships for Transfer Learning on Chatbot-based Question Answering Systems
**author**:Jianfei Yu, Minghui Qiu, Jing Jiang, Jun Huang,      Wei Chu, Haiqing Chen

**abstract**:Nowadays,it is a heated topic for many industries to build automatic question-answering (QA) systems. A key solution to these QA systems is to retrieve from a QA knowledge base the most similar question of a given question, which can be reformulated
as a paraphrase identification (PI) or a natural language inference (NLI) problem. However, most existing models for PI and NLI have at least two problems: They rely on a large amount of labeled data,
which is not always available in real scenarios, and they may not be efficient for industrial applications.
In this paper, we study transfer learning for the PI and NLI problems, aiming to propose a general framework, which can effectively and efficiently adapt the shared knowledge learned from a resource-rich source domain to a resource-poor target domain.
Specifically, since most existing transfer learning methods only focus on learning a shared feature space across domains while ignoring the relationship between the source and target domains, we propose to simultaneously learn shared representations and domain
relationships in a unified framework. Furthermore, we propose an efficient and effective hybrid model by combining a sentence encoding-based method and a sentence interaction-based method as our base model. Extensive experiments on both paraphrase identification and natural language inference demonstrate that our base model is efficient and has promising performance compared to the competing models, and our transfer learning method can help to significantly boost the performance. Further analysis shows that the inter-domain and intra-domain relationship captured by our
model are insightful. Last but not least, we deploy our transfer learning model for PI into our online chatbot system, which can bring in significant improvements over our existing system.

**keywords**: 

**interpretation**:

**pdf**: [paper](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4966&context=sis_research)

**code**:

**dataset**:

**ppt/video**:

**curator**: Ranran Chu
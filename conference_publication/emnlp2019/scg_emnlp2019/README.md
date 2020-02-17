# Patient Knowledge Distillation for BERT Model Compression

- **author**:Siqi Sun, Yu Cheng, Zhe Gan, Jingjing Liu 

- **abstract**: Pre-trained language models such as BERT have proven to be highly effective for natural language processing (NLP) tasks. However, the high demand for computing resources in training such models hinders their application in practice. In order to alleviate this resource hunger in large-scale model training, we propose a Patient Knowledge Distillation approach to compress an original large model (teacher) into an equally-effective lightweight shallow network (student). Different from previous knowledge distillation methods, which only use the output from the last layer of the teacher network for distillation, our student model patiently learns from multiple intermediate layers of the teacher model for incremental knowledge extraction, following two strategies: (*[Math Processing Error]*) PKD-Last: learning from the last *[Math Processing Error]* layers; and (*[Math Processing Error]*) PKD-Skip: learning from every *[Math Processing Error]* layers. These two patient distillation schemes enable the exploitation of rich information in the teacher's hidden layers, and encourage the student model to patiently learn from and imitate the teacher through a multi-layer distillation process. Empirically, this translates into improved results on multiple NLP tasks with significant gain in training efficiency, without sacrificing model accuracy. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1908.09355)

- **code**: [code](https://github.com/intersun/PKD-for-BERT-Model-Compression)  

- **dataset**: SST-2,MRPC,QQP,MNLI,QNLI,RTE

- **ppt/video**:

- **curator**: Yawen Dai
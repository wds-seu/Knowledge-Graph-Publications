# Answering Conversational Questions on Structured Data without Logical Forms

- **author**:Thomas Muller,Francesco Piccinno,Massimo Nicosia,Peter Shaw,Yasemin Altun
- **abstract**: We present a novel approach to answering sequential questions based on structured objects such as knowledge bases or tables without using a logical form as an intermediate representation. We encode tables as graphs using a graph neural network model based on the Transformer architecture. The answers are then selected from the encoded graph using a pointer network. This model is appropriate for processing conversations around structured data, where the attention mechanism that selects the answers to a question can also be used to resolve conversational references. We demonstrate the validity of this approach with competitive results on the Sequential Question Answering (SQA) task (Iyyer et al., 2017). 
- **keywords**:
- **interpretation**:
- **pdf**: [pdf](https://arxiv.org/pdf/1908.11787)
- **code**:
- **dataset**:SequentialQA (SQA) dataset
- **ppt/video**:
- **curator**: Yawen Dai
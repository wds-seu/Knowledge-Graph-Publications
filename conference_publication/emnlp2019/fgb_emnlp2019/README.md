# Using Local Knowledge Graph Construction to Scale Seq2Seq Models to Multi-Document Inputs

- **author**:Angela Fan,Claire Gardent,Chloe Braud, Antoine Bordes
- **abstract**: Query-based open-domain NLP tasks require information synthesis from long and diverse web results. Current approaches extractively select portions of web text as input to Sequence-to-Sequence models using methods such as TF-IDF ranking. We propose constructing a local graph structured knowledge base for each query, which compresses the web search information and reduces redundancy. We show that by linearizing the graph into a structured input sequence, models can encode the graph representations within a standard Sequence-to-Sequence setting. For two generative tasks with very long text input, long-form question answering and multi-document summarization, feeding graph representations as input can achieve better performance than using retrieved text portions. 
- **keywords**:
- **interpretation**:
- **pdf**: [pdf](https://arxiv.org/pdf/1910.08435)
- **code**:
- **dataset**: ELI5, WikiSum
- **ppt/video**:
- **curator**: Yawen Dai

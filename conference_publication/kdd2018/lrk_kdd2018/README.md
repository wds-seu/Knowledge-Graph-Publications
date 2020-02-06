# Graph Classification using Structural Attention
- **author**: John Boaz Lee (WPI); Ryan Rossi (Adobe Research); Xiangnan Kong (WPI)
- **abstract**: Graph classification is a problem with practical applications in many different domains. To solve this problem, one usually calculates certain graph statistics (i.e., graph features) that help discriminate between graphs of different classes. When calculating such features, most existing approaches process the entire graph. In a graphlet-based approach, for instance, the entire graph is processed to get the total count of different graphlets or subgraphs. In many real-world applications, however, graphs can be noisy with discriminative patterns confined to certain regions in the graph only. In this work, we study the problem of attention-based graph classification. The use of attention allows us to focus on small but informative parts of the graph, avoiding noise in the rest of the graph. We present a novel RNN model, called the Graph Attention Model (GAM), that processes only a portion of the graph by adaptively selecting a sequence of “informative” nodes. Experimental results on multiple real-world datasets show that the proposed method is competitive against various well-known methods in graph classification even though our method is limited to only a portion of the graph.
- **keywords**:Attentional processing, graph mining, reinforcement learning, deep learning
- **interpretation**:
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3219819.3219980?download=true)
- **code**: [code](https://github.com/benedekrozemberczki/GAM)
- **dataset**: HIV,NCI1,NCI-33,NCI-83,NCI-123 
- **ppt/video**:
- **curator**: Mengya Ji

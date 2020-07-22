# Knowledge Hypergraphs: Prediction Beyond Binary Relations
* **author**: Bahare Fatemi, Perouz Taslakian, David Vazquez, David Poole
* **abstract**: Knowledge graphs store facts using relations between two entities. In this work, we address the question of link prediction in knowledge hypergraphs where relations are defined on any number of entities. While techniques exist (such as reification) that convert non-binary relations into binary ones, we show that current embedding-based methods for knowledge graph completion do not work well out of the box for knowledge graphs obtained through these techniques. To overcome this, we introduce HSimplE and HypE, two embedding-based methods that work directly with knowledge hypergraphs. In both models, the prediction is a function of the relation embedding, the entity embeddings and their corresponding positions in the relation. We also develop public datasets, benchmarks and baselines for hypergraph prediction and show experimentally that the proposed models are more effective than the baselines.
* **keywords**: multiple relation prediction
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.ijcai.org/Proceedings/2020/303)
* **code**: [link](https://github.com/ElementAI/HypE)
* **dataset**: JF17K, FB-AUTO, M-FB15K, WN18, FB15K
* **ppt/video**:
* **curation**: Jiong Zhang 
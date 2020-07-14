# Ariadne: Online Provenance for Big Graph Analytics
* **author**: Vicky Papavasileiou, Ken Yocum, Alin Deutsch
* **abstract**: Data provenance is a powerful tool for debugging large-scale analytics on batch processing systems. This paper presents Ariadne, a system for capturing and querying provenance from Vertex-Centric graph processing systems. While the size of provenance from map-reduce-style workflows is often a fraction of the input data size, graph algorithms iterate over the input graph many times, producing provenance much larger than the input graph. And though current provenance tracing procedures support explicit debugging scenarios, like crash-culprit determination, developers are increasingly interested in the behavior of analytics when a crash or exception does not occur. To address this challenge, Ariadne offers developers a concise declarative query language to capture and query graph analytics provenance. Exploiting the formal semantics of this datalog-based language, we identify useful query classes that can run while an analytic computes. Experiments with various analytics and real-world datasets show the overhead of online querying is 1.3x over the baseline vs. 8x for the traditional approach. These experiments also illustrate how Ariadne's query language supports execution monitoring and performance optimization for graph analytics.
* **keywords**: graph provenance
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://dl.acm.org/doi/10.1145/3299869.3300091)
* **code**: 
* **dataset**: indochina-2004 (IN04), uk-2002 (UK-02), arabic (AR-05), uk-2005 (UK-05), MovieLens 20M
* **ppt/video**:
* **curation**: Jiong Zhang 
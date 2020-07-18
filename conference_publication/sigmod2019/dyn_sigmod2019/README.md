# Hypothetical Reasoning via Provenance Abstraction
* **author**: Daniel Deutch, Yuval Moskovitch, Noam Rinetzky
* **abstract**: Data analytics often involves hypothetical reasoning: repeatedly modifying the data and observing the induced effect on the computation result of a data-centric application. Previous work has shown that fine-grained data provenance can help make such an analysis more efficient: instead of a costly re-execution of the underlying application, hypothetical scenarios are applied to a pre-computed provenance expression. However, storing provenance for complex queries and large-scale data leads to a significant overhead, which is often a barrier to the incorporation of provenance-based solutions. To this end, we present a framework that allows to reduce provenance size. Our approach is based on reducing the provenance granularity using user defined abstraction trees over the provenance variables; the granularity is based on the anticipated hypothetical scenarios. We formalize the tradeoff between provenance size and supported granularity of the hypothetical reasoning, and study the complexity of the resulting optimization problem, provide efficient algorithms for tractable cases and heuristics for others. We experimentally study the performance of our solution for various queries and abstraction trees. Our study shows that the algorithms generally lead to substantial speedup of hypothetical reasoning, with a reasonable loss of accuracy.
* **keywords**: provenance, hypothetical reasoning
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://dl.acm.org/doi/10.1145/3299869.3300084)
* **code**: 
* **dataset**:
* **ppt/video**:
* **curation**: Jiong Zhang 
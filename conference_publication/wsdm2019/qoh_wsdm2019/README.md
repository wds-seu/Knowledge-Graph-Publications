# Discovering Correlations between Sparse Features in Distant Supervision for Relation Extraction
* **author**: Jianfeng Qu, Dantong Ouyang, Wen Hua, Yuxin Ye, Xiaofang Zhou
* **abstract**: The recent art in relation extraction is distant supervision which generates training data by heuristically aligning a knowledge base with free texts and thus avoids human labelling. However, the concerned relation mentions often use the bag-of-words representation, which ignores inner correlations between features located in different dimensions and makes relation extraction less effective. To capture the complex characteristics of relation expression and tighten the correlated features, we attempt to discover and utilise informative correlations between features by the following four phases: 1) formulating semantic similarities between lexical features using the embedding method; 2) constructing generative relation for lexical features with different sizes of side windows; 3) computing correlation scores between syntactic features through a kernel-based method; and 4) conducting a distillation process for the obtained correlated feature pairs and integrating informative pairs with existing relation extraction models. The extensive experiments demonstrate that our method can effectively discover correlation information and improve the performance of state-of-the-art relation extraction methods.
* **keywords**: relation extraction
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://dl.acm.org/doi/pdf/10.1145/3289600.3291004?download=true)
* **code**: [暂无]()
* **dataset**: FreeBase, NYT
* **ppt/video**:
* **curation**: Jiong Zhang 
## Multi-lingual Common Semantic Space Construction via Cluster-consistent Word Embedding

**author**:Lifu Huang,Kyunghyun Cho,Boliang Zhang,Heng Ji,Kevin Knight

**abstract**:We construct a multilingual common semantic space based on distributional semantics, where
words from multiple languages are projected into a shared space via which all available resources and knowledge can be shared across multiple languages. Beyond word alignment, we introduce multiple cluster-level alignments and enforce the word clusters to be consistently distributed across multiple languages.
We exploit three signals for clustering: (1) neighbor words in the monolingual word embedding space; (2) character-level information; and (3) linguistic properties (e.g., apposition, locative suffix) derived from linguistic structure knowledge bases available for
thousands of languages. We introduce a new cluster-consistent correlational neural network to construct the common semantic space by aligning words as well as clusters. Intrinsic evaluation on monolingual and multilingual QVEC tasks shows our approach achieves
significantly higher correlation with linguistic features which are extracted from manually crafted lexical resources than state-of-the-art multi-lingual embedding learning methods do. Using low-resource language name tagging as a case study for extrinsic evaluation, our approach achieves up to 14.6% absolute F-score gain over the state of the art on cross-lingual
direct transfer. Our approach is also shown to be robust even when the size of bilingual dictionary is small.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1023.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
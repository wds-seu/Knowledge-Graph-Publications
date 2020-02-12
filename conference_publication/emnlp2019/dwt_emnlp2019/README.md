# Learning to Infer Entities, Properties and their Relations from Clinical Conversations

- **author**:Nan Du, Mingqiu Wang, Linh Tran, Gang Li, Izhak Shafran 
- **abstract**: Recently we proposed the Span Attribute Tagging (SAT) Model (Du et al., 2019) to infer clinical entities (e.g., symptoms) and their properties (e.g., duration). It tackles the challenge of large label space and limited training data using a hierarchical two-stage approach that identifies the span of interest in a tagging step and assigns labels to the span in a classification step. 
  We extend the SAT model to jointly infer not only entities and their properties but also relations between them. Most relation extraction models restrict inferring relations between tokens within a few neighboring sentences, mainly to avoid high computational complexity. In contrast, our proposed Relation-SAT (R-SAT) model is computationally efficient and can infer relations over the entire conversation, spanning an average duration of 10 minutes. 
  We evaluate our model on a corpus of clinical conversations. When the entities are given, the R-SAT outperforms baselines in identifying relations between symptoms and their properties by about 32% (0.82 vs 0.62 F-score) and by about 50% (0.60 vs 0.41 F-score) on medications and their properties. On the more difficult task of jointly inferring entities and relations, the R-SAT model achieves a performance of 0.34 and 0.45 for symptoms and medications respectively, which is significantly better than 0.18 and 0.35 for the baseline model. The contributions of different components of the model are quantified using ablation analysis.  
- **keywords**:
- **interpretation**:
- **pdf**: [pdf](https://arxiv.org/pdf/1908.11536)
- **code**:
- **dataset**:
- **ppt/video**:
- **curator**: Yawen Dai
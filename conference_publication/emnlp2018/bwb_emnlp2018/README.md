## Commonsense for Generative Multi-Hop Question Answering Tasks

**author**:Lisa Bauer, Yicheng Wang, Mohit Bansal

**abstract**:Reading comprehension QA tasks have seen
a recent surge in popularity, yet most works have focused on fact-finding extractive QA. We instead focus on a more challenging multihop generative task (NarrativeQA), which requires the model to reason, gather, and synthesize disjoint pieces of information within the context to generate an answer. This type of
multi-step reasoning also often requires understanding implicit relations, which humans resolve via external, background commonsense knowledge. We first present a strong generative baseline that uses a multi-attention mechanism to perform multiple hops of reasoning and a pointer-generator decoder to synthesize the answer. This model performs substantially better than previous generative models, and is competitive with current state-of-the-art span prediction models. We next introduce a novel system for selecting grounded multi-hop relational commonsense information from ConceptNet via a pointwise mutual information and term-frequency based scoring function. Finally, we effectively use this extracted commonsense information to fill in gaps of reasoning between context hops, using a selectivelygated attention mechanism. This boosts the
model’s performance significantly (also verified via human evaluation), establishing a new state-of-the-art for the task. We also show that our background knowledge enhancements are generalizable and improve performance on QAngaroo-WikiHop, another multi-hop reasoning dataset.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1454.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
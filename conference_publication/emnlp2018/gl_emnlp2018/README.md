## Neural Compositional Denotational Semantics for Question Answering

**author**:Nitish Gupta, Mike Lewis

**abstract**:Answering compositional questions requiring multi-step reasoning is challenging. We introduce an end-to-end differentiable model for interpreting questions about a knowledge graph (KG), which is inspired by formal approaches to semantics. Each span of text is represented by a denotation in a KG and a vector that captures ungrounded aspects of meaning. Learned composition modules recursively
combine constituent spans, culminating in a grounding for the complete sentence which answers the question. For example, to interpret “not green”, the model represents “green” as a set of KG entities and “not” as a trainable ungrounded vector—and then uses this vector to parameterize a composition function that performs a complement operation. For each sentence, we build a parse chart subsuming all possible parses, allowing the model to jointly learn both the composition operators and output structure by gradient descent from endtask supervision. The model learns a variety of challenging semantic operators, such as quantifiers, disjunctions and composed relations, and infers latent syntactic structure. It also generalizes well to longer questions than seen in its training data, in contrast to RNN, its treebased variants, and semantic parsing baselines.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1239.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
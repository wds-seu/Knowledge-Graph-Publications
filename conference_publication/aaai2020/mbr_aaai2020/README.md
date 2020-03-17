# Differentiable Reasoning on Large Knowledge Bases and Natural Language

* **author**:Pasquale Minervini, Matko Bošnjak, Tim Rocktäschel, Sebastian Riedel, Edward Grefenstette
* **abstract**:Reasoning with knowledge expressed in natural language and Knowledge Bases (KBs) is a major challenge for Artificial Intelligence, with applications in machine reading, dialogue, and question answering. General neural architectures that jointly learn representations and transformations of text are very data-inefficient, and it is hard to analyse their reasoning process. These issues are addressed by end-to-end differentiable reasoning systems such as Neural Theorem Provers (NTPs), although they can only be used with small-scale symbolic KBs. In this paper we first propose Greedy NTPs (GNTPs), an extension to NTPs addressing their complexity and scalability limitations, thus making them applicable to real-world datasets. This result is achieved by dynamically constructing the computation graph of NTPs and including only the most promising proof paths during inference, thus obtaining orders of magnitude more efficient models. Then, we propose a novel approach for jointly reasoning over KBs and textual mentions, by embedding logic facts and natural language sentences in a shared embedding space. We show that GNTPs perform on par with NTPs at a fraction of their cost while achieving competitive link prediction results on large datasets, providing explanations for predictions, and inducing interpretable models. Source code, datasets, and supplementary material are available online at [this https URL](https://github.com/uclnlp/gntp).
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1912.10824.pdf)
* **code**:
* **dataset**:Countries,Kinship,Nations,UMLS
* **ppt/video**:
* **curator**:Shuwei Yuan
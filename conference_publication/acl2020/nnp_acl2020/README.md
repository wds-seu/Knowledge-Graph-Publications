# A Relational Memory-based Embedding Model for Triple Classification and Search Personalization

* **author**: Dai Quoc Nguyen, Tu Dinh Nguyen, Dinh Phung
* **abstract**: Knowledge graph embedding methods often suffer from a limitation of memorizing valid triples to predict new ones for triple classification and search personalization problems. To this end, we introduce a novel embedding model, named R-MeN, that explores a relational memory network to encode potential dependencies in relationship triples. R-MeN considers each triple as a sequence of 3 input vectors that recurrently interact with a memory using a transformer self-attention mechanism. Thus R-MeN encodes new information from interactions between the memory and each input vector to return a corresponding vector. Consequently, R-MeN feeds these 3 returned vectors to a convolutional neural network-based decoder to produce a scalar score for the triple. Experimental results show that our proposed R-MeN obtains state-of-the-art results on SEARCH17 for the search personalization task, and on WN11 and FB13 for the triple classification task.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1907.06080)
* **code**:[github](https://github.com/daiquocnguyen/R-MeN)
* **dataset**:WN11,FB13
* **ppt/video**:
* **curator**:Shuwei Yuan


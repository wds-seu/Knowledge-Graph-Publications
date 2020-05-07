## Neural Relation Extraction via Inner-Sentence Noise Reduction and Transfer Learning

**author**:Tianyi Liu, Xinsong Zhang, Wanhao Zhou, Weijia Jia

**abstract**:Extracting relations is critical for knowledge base completion and construction in which
distant supervised methods are widely used to extract relational facts automatically with the existing knowledge bases. However, the automatically constructed datasets comprise amounts of low-quality sentences containing noisy words, which is neglected by current
distant supervised methods resulting in unacceptable precisions. To mitigate this problem, we propose a novel word-level distant supervised approach for relation extraction. We first build Sub-Tree Parse (STP) to remove noisy words that are irrelevant to relations. Then we construct a neural network inputting the subtree while applying the entity-wise attention to
identify the important semantic features of relational words in each instance. To make our model more robust against noisy words, we initialize our network with a priori knowledge learned from the relevant task of entity classification by transfer learning. We conduct extensive experiments using the corpora of New
York Times (NYT) and Freebase. Experiments show that our approach is effective and improves the area of Precision/Recall (PR) from 0.35 to 0.39 over the state-of-the-art work.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1243.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
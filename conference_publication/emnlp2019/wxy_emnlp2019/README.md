#  Learning to Learn and Predict: A Meta-Learning Approach for Multi-Label Classification 

- **author**:Jiawei Wu, Wenhan Xiong, William Yang Wang 

- **abstract**: Many tasks in natural language processing can be viewed as multi-label classification problems. However, most of the existing models are trained with the standard cross-entropy loss function and use a fixed prediction policy (e.g., a threshold of 0.5) for all the labels, which completely ignores the complexity and dependencies among different labels. In this paper, we propose a meta-learning method to capture these complex label dependencies. More specifically, our method utilizes a meta-learner to jointly learn the training policies and prediction policies for different labels. The training policies are then used to train the classifier with the cross-entropy loss function, and the prediction policies are further implemented for prediction. Experimental results on fine-grained entity typing and text classification demonstrate that our proposed method can obtain more accurate multi-label classification results.  

- **keywords**:

- **interpretation**: [review](https://blog.csdn.net/a1424262219/article/details/102148729)

- **pdf**: [pdf](https://arxiv.org/pdf/1909.04176)

- **code**:

- **dataset**:FIGER, OntoNotes , BBN 

- **ppt/video**:

- **curator**: Yawen Dai

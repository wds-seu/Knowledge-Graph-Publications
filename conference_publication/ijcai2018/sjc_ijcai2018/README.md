# Exploring Encoder-Decoder Model for Distant Supervised Relation Extraction
* **author**：Sen Su, Ningning Jia, Xiang Cheng, Shuguang Zhu, Ruiping Li
* **abstract**: In this paper, we present an encoder-decoder model for distant supervised relation extraction. Given an entity pair and its sentence bag as input, in the encoder component, we employ the convolutional neural network to extract the features of the sentences in the sentence bag and merge them into a bag representation. In the decoder component, we utilize the long short-term memory network to model relation dependencies and predict the target relations in a sequential manner. In particular, to enable the sequential prediction of relations, we introduce a measure to quantify the amounts of information the relations take in their sentence bag, and use such information to determine the order of the relations of a sentence bag during model training. Moreover, we incorporate the attention mechanism into our model to dynamically adjust the bag representation to reduce the impact of sentences whose corresponding relations have been predicted. Extensive experiments on a popular dataset show that our model achieves significant improvement over state-of-the-art methods.
* **keywords**: Neural Networks, Information Extraction, Multi-instance, Multi-view learning, Deep Learning, Knowledge Extraction
* **interpretation**: 
* **pdf**:  [link](https://www.ijcai.org/Proceedings/2018/0610.pdf)
* **code**: 
* **dataset**: NYT
* **ppt/video**: 
* **curator**: Chang Liu

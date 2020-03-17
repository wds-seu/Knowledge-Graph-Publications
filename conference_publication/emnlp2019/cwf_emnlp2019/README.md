# Enhancing Neural Data-To-Text Generation Models with External Background Knowledge

- **author**:Shuang Chen,Jinpeng Wang,Xiaocheng Feng,Feng Jiang,Bing Qin,Chin-Yew Lin

- **abstract**: Recent neural models for data-to-text generation rely on massive parallel pairs of data and text to learn the writing knowledge. They often assume that writing knowledge can be acquired from the training data alone. However, when people are writing, they not only rely on the data but also consider related knowledge. In this paper, we enhance neural data-to-text models with external knowledge in a simple but effective way to improve the fidelity of generated text. Besides relying on parallel data and text as in previous work, our model attends to relevant external knowledge, encoded as a temporary memory, and combines this knowledge with the context representation of data before generating words. This allows the model to infer relevant facts which are not explicitly stated in the data table from an external knowledge source. Experimental results on twenty-one Wikipedia infobox-to-text datasets show our model, KBAtt, consistently improves a state-of-the-art model on most of the datasets. In addition, to quantify when and why external knowledge is effective, we design a metric, KBGain, which shows a strong correlation with the observed performance boost. This result demonstrates the relevance of external knowledge and sparseness of original data are the main factors affecting system performance. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf]( https://www.aclweb.org/anthology/D19-1299.pdf )

- **code**: [code](https://github.com/hitercs/WikiInfo2Text)

- **dataset**: WikiBio,twenty new infoboxto-text datasets collected from Wikipedia

- **ppt/video**:

- **curator**: Yawen Dai
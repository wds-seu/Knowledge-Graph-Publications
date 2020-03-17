# Event Causality Recognition Exploiting Multiple Annotators’ Judgments and Background Knowledge

- **author**:Kazuma Kadowaki,Ryu Iida,Kentaro Torisawa, Jong-Hoon Oh, Julien Kloetzer

- **abstract**: We propose new BERT-based methods for recognizing event causality such as “smoke cigarettes” –> “die of lung cancer” written in web texts. In our methods, we grasp each annotator’s policy by training multiple classifiers, each of which predicts the labels given by a single annotator, and combine the resulting classifiers’ outputs to predict the final labels determined by majority vote. Furthermore, we investigate the effect of supplying background knowledge to our classifiers. Since BERT models are pre-trained with a large corpus, some sort of background knowledge for event causality may be learned during pre-training. Our experiments with a Japanese dataset suggest that this is actually the case: Performance improved when we pre-trained the BERT models with web texts containing a large number of event causalities instead of Wikipedia articles or randomly sampled web texts. However, this effect was limited. Therefore, we further improved performance by simply adding texts related to an input causality candidate as background knowledge to the input of the BERT models. We believe these findings indicate a promising future research direction. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://www.aclweb.org/anthology/D19-1590.pdf )

- **code**: 

- **dataset**:  event-causality recognition in Japanese of Hashimoto et al. 

- **ppt/video**:

- **curator**: Yawen Dai
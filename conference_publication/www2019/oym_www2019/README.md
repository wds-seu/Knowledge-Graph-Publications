# ActiveLink: Deep Active Learning for Link Prediction in Knowledge Graphs 
- **author**: Natalia Ostapuk, Jie Yang, Philippe Cudre-Mauroux  
- **abstract**: Neural networks have recently been shown to be highly effective at predicting links for constructing knowledge graphs. Existing research has mainly focused on designing 1) deep neural network models that are expressive in capturing fine-grained semantics, e.g., NTN and ConvE, but that are however less scalable; or 2) shallow models that are scalable, e.g., TransE and DistMult, yet limited in capturing expressive semantic features. In this work, we demonstrate that we can get the best of both worlds while drastically reducing the amount of data needed to train a deep network by leveraging active learning.   
We present a novel deep active learning framework, ActiveLink, which can be applied to actively train any neural link predictor. Inspired by recent advances in Bayesian deep learning, ActiveLink takes a Bayesian view on neural link predictors, thereby enabling uncertainty sampling for deep active learning. ActiveLink extends uncertainty sampling by exploiting the underlying structure of the knowledge graph, i.e., links between entities, to improve sampling effectiveness. To accelerate model training, ActiveLink further adopts an incremental training method that allows deep neural networks to be incrementally trained while optimizing their generalizability at each iteration. Extensive validation on real-world datasets shows that ActiveLink is able to match state-of-the-art approaches while requiring only 20% of the original training data.  
- **keywords**: Deep active learning; neural link prediction; incremental training 
- **interpretation**: 
- **pdf**: [paper](https://yangjiera.github.io/works/WWW2019b.pdf)
- **code**: [githun](https://github.com/eXascaleInfolab/ActiveLink)
- **dataset**: FB15K237, WikiMovie
- **ppt/video**:
- **curator**: Xiaoyu Shang 

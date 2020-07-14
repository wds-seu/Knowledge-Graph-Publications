# Feature-map-level Online Adversarial Knowledge Distillation
- **author**: Inseop Chung,  SeongUk Park,  Jangho Kim, Nojun Kwak 
- **abstract**: Feature maps contain rich information about image intensity and spatial correlation. However, previous online knowledge distillation methods only utilize the class probabilities. Thus in this paper, we propose an online knowledge distillation method that transfers not only the knowledge of the class probabilities but also that of the feature map using the adversarial training framework. We train multiple networks simultaneously by employing discriminators to distinguish the feature map distributions of different networks. Each network has its corresponding discriminator which discriminates the feature map from its own as fake while classifying that of the other network as real. By training a network to fool the corresponding discriminator, it can learn the other network’s feature map distribution. We show that our method performs better than the conventional direct alignment method such as L1 and is more suitable for online distillation. Also, we propose a novel cyclic learning scheme for training more than two networks together. We have applied our method to various network architectures on the classification task and discovered a significant improvement of performance especially in the case of training a pair of a small network and a large one.
- **keywords**: 
- **interpretation**: []()
- **pdf**: [paper](https://proceedings.icml.cc/static/paper_files/icml/2020/143-Paper.pdf)
- **code**: [code]()
- **dataset**:  CIFAR-100
- **ppt/video**:
- **curator**: Mengya Ji

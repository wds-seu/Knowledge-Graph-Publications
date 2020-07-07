# Zero-Shot Knowledge Distillation in Deep Networks
- **author**: Gaurav Kumar Nayak  Konda Reddy Mopuri  Vaisakh Shaj  R. Venkatesh Babu 
  Anirban Chakraborty 
- **abstract**: Knowledge distillation deals with the problem of training a smaller model (Student) from a high capacity source model (Teacher) so as to retain most of its performance. Existing approaches use either the training data or meta-data extracted from it in order to train the Student. However, accessing the dataset on which the Teacher has been trained may not always be feasible if the dataset is very large or it poses privacy or safety concerns (e. g. , bio-metric or medical data). Hence, in this paper, we propose a novel data-free method to train the Student from the Teacher. Without even using any meta-data, we synthesize the Data Impressions from the complex Teacher model and utilize these as surrogates for the original training data samples to transfer its learning to Student via knowledge distillation. We, therefore, dub our method “Zero-Shot Knowledge Distillation” and demonstrate that our framework results in competitive generalization performance as achieved by distillation using the actual training data samples on multiple benchmark datasets.
- **keywords**: Knowledge distillation  data-free 
- **interpretation**:
- **pdf**: [paper](https://arxiv.org/pdf/1905.08114.pdf)
- **code**: 
- **dataset**: MNIST、Fashion MNIST、CIFAR-10
- **ppt/video**:
- **curator**: Jidong He

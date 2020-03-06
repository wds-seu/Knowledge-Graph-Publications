# GRN: Gated Relation Network to Enhance Convolutional Neural Network for Named Entity Recognition 
- **author**: Hui Chen, Zijia Lin, Guiguang Ding, Jianguang Lou, Yusen Zhang, Börje Karlsson  
- **abstract**: The dominant approaches for named entity recognitionm (NER) mostly adopt complex recurrent neural networks (RNN), e.g., long-short-term-memory (LSTM). However, RNNs are limited by their recurrent nature in terms of computational efficiency. In contrast, convolutional neural networks (CNN) can fully exploit the GPU parallelism with their feedforward architectures. However, little attention has been paid to performing NER with CNNs, mainly owing to their difficulties in capturing the long-term context information in a sequence. In this paper, we propose a simple but effective CNN-based network for NER, i.e., gated relation network (GRN), which is more capable than common CNNs in capturing long-term context. Specifically, in GRN we firstly employ CNNs to explore the local context features of each word. Then we model the relations between words and use them as gates to fuse local context features into global ones for predicting labels. Without using recurrent layers that process a sentence in a sequential manner, our GRN allows computations to be performed in parallel across the entire sentence. Experiments on two benchmark NER datasets (i.e., CoNLL2003 and Ontonotes 5.0) show that, our proposed GRN can achieve state-of-the-art performance with or without external knowledge. It also enjoys lower time costs to train and test.
- **keywords**: 
- **interpretation**: [CSDN](https://blog.csdn.net/qq_38244371/article/details/90519938)
- **pdf**: [paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4583/4461)
- **code**: [github](https://github.com/HuiChen24/NER-GRN)
- **dataset**: CoNLL-2003, OnetoNotes 5.0
- **ppt/video**:
- **curator**: Xiaoyu Shang

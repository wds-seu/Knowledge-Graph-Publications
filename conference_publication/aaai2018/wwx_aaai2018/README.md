# Knowledge Enhanced Hybrid Neural Network for Text Matching
* **author**: Yu Wu, Wei Wu, Can Xu, Zhoujun Li
* **abstract**: Long text brings a big challenge to neural network based text matching approaches due to their complicated structures. To tackle the challenge, we propose a knowledge enhanced hybrid neural network (KEHNN) that leverages prior knowledge to identify useful information and filter out noise in long text and performs matching from multiple perspectives. The model fuses prior knowledge into word representations by knowledge gates and establishes three matching channels with words, sequential structures of text given by Gated Recurrent Units (GRUs), and knowledge enhanced representations. The three channels are processed by a convolutional neural network to generate high level features for matching, and the features are synthesized as a matching score by a multilayer perceptron. In this paper, we focus on exploring the use of taxonomy knowledge for text matching. Evaluation results from extensive experiments on public data sets of question answering and conversation show that KEHNN can significantly outperform state-of-the-art matching models and particularly improve matching accuracy on pairs with long text.
* **keywords**: Text Matching
* **interpretation**: [来源: CSDN](https://blog.csdn.net/qq_36891953/article/details/81253367) [来源: 知乎](https://zhuanlan.zhihu.com/p/35432018)
* **pdf**: [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16225/16116)
* **code**: [暂无]()
* **dataset**: QA, Ubuntu
* **ppt/video**:
* **curation**: Jiong Zhang 
#Enhancing Conversational Dialogue Models with Grounded Knowledge.
- **author**:Wen Zheng, Ke Zhou  
- **abstract**:Leveraging external knowledge to enhance conversational models has become a popular research area in recent years. Compared to vanilla generative models, the knowledge-grounded models may produce more informative and engaging responses. Although various approaches have been proposed in the past, how to effectively incorporate knowledge remains an open research question. It is unclear how much external knowledge should be retrieved and what is the optimal way to enhance the conversational model, trading off between relevant information and noise. Therefore, in this paper, we aim to bridge the gap by first extensively evaluating various types of state-of-the-art knowledge-grounded conversational models, including recurrent neural network based, memory networks based, and Transformer based models. We demonstrate empirically that those conversational models can only be enhanced with the right amount of external knowledge. To effectively leverage information originated from external knowledge, we propose a novel Transformer with Expanded Decoder (Transformer-ED or TED for short), which can automatically tune the weights for different sources of evidence when generating responses. Our experiments show that our proposed model outperforms state-of-the-art models in terms of both quality and diversity.
- **keywords**:copy-mechanism ，generative model ，knowledge-grounded ，memory network， multi-task learning ，sequence-to-sequence， ted transformer ，transformer-ed
- **interpretation**:
- **pdf**:[paper](https://dl.acm.org/doi/pdf/10.1145/3357384.3357889)
- **code**: 
- **dataset**: Reddit and Wizard of Wikipedia
- **ppt/video**:
- **curator**: Wu Bo
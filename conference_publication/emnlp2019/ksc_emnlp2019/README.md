#  What's Missing: A Knowledge Gap Guided Approach for Multi-hop Question Answering 

- **author**:Tushar Khot,Ashish Sabharwal ,Peter Clark 

- **abstract**: Multi-hop textual question answering requires combining information from multiple sentences. We focus on a natural setting where, unlike typical reading comprehension, only partial information is provided with each question. The model must retrieve and use additional knowledge to correctly answer the question. To tackle this challenge, we develop a novel approach that explicitly identifies the knowledge gap between a key span in the provided knowledge and the answer choices. The model, GapQA, learns to fill this gap by determining the relationship between the span and an answer choice, based on retrieved knowledge targeting this gap. We propose jointly training a model to simultaneously fill this knowledge gap and compose it with the provided partial knowledge. On the OpenBookQA dataset, given partial knowledge, explicitly identifying what's missing substantially outperforms previous approaches.  

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1909.09253)

- **code**: [code](https://github.com/allenai/missing-fact)  

- **dataset**: KGD

- **ppt/video**:

- **curator**: Yawen Dai
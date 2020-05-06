# A Fine-grained and Noise-aware Method for Neural Relation Extraction
- **author**: 	Jianfeng Qu, Wen Hua, Dantong Ouyang, Xiaofang Zhou, Ximing Li   
- **abstract**: Distant supervision is an efficient way to generate large-scale training data for relation extraction without human efforts. However, a coin has two sides. The automatically annotated labels for training data are problematic, which can be summarized as multi-instance multi-label problem and coarse-grained (bag-level) supervised signal. To address these problems, we propose two reasonable assumptions and craft reinforcement learning to capture the expressive sentence for each relation mentioned in a bag. More specifically, we extend the original expressed-at-least-once assumption to multi-label level, and introduce a novel express-at-most-one assumption. Besides, we design a fine-grained reward function, and model the sentence selection process as an auction where different relations for a bag need to compete together to achieve the possession of a specific sentence based on its expressiveness. In this way, our model can be dynamically self-adapted, and eventually implements the accurate one-to-one mapping from a relation label to its chosen expressive sentence, which serves as training instances for the extractor. The experimental results on a public dataset demonstrate that our model constantly and substantially outperforms current state-of-the-art methods for relation extraction.
- **keywords**:coarse-grained supervised signal， distant supervision， multi-instance multi-label， reinforcement learning，relation extraction
- - **interpretation**:
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3357384.3357997)
- **code**: 
- **dataset**: 
- **ppt/video**:
- **curator**: Wu Bo
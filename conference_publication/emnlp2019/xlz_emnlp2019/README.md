# A Syntax-aware Multi-task Learning Framework for Chinese Semantic Role Labeling

- **author**:Qingrong Xia,Zhenghua Li,Min Zhang 
- **abstract**: Semantic role labeling (SRL) aims to identify the predicate-argument structure of a sentence. Inspired by the strong correlation between syntax and semantics, previous works pay much attention to improve SRL performance on exploiting syntactic knowledge, achieving significant results. Pipeline methods based on automatic syntactic trees and multi-task learning (MTL) approaches using standard syntactic trees are two common research orientations. In this paper, we adopt a simple unified span-based model for both span-based and word-based Chinese SRL as a strong baseline. Besides, we present a MTL framework that includes the basic SRL module and a dependency parser module. Different from the commonly used hard parameter sharing strategy in MTL, the main idea is to extract implicit syntactic representations from the dependency parser as external inputs for the basic SRL model. Experiments on the benchmarks of Chinese Proposition Bank 1.0 and CoNLL-2009 Chinese datasets show that our proposed framework can effectively improve the performance over the strong baselines. With the external BERT representations, our framework achieves new state-of-the-art 87.54 and 88.5 F1 scores on the two test data of the two benchmarks, respectively. In-depth analysis are conducted to gain more insights on the proposed framework and the effectiveness of syntax. 
- **keywords**:
- **interpretation**:待补充
- **pdf**: [pdf](https://www.aclweb.org/anthology/D19-1541.pdf)
- **code**: [code](https://github.com/KiroSummer/A_Syntax-aware_MTL_Framework_for_Chinese_SRL/tree/4c0ab4d1a2859a66508ed80e9c633f3859c317da)
- **dataset**:Chinese Proposition Bank 1.0,CoNLL-2009 Chinese datasets
- **ppt/video**:
- **curator**: Yawen Dai
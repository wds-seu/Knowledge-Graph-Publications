# Zero-Shot Neural Transfer for Cross-Lingual Entity Linking 
- **author**: Shruti Rijhwani, Jiateng Xie, Graham Neubig, Jaime G. Carbonell  
- **abstract**: ross-lingual entity linking maps an entity mention in a source language to its corresponding entry in a structured knowledge base that is in a different (target) language. While previous work relies heavily on bilingual lexical resources to bridge the gap between the source and the target languages, these resources are scarce or unavailable for many low-resource languages. To address this problem, we investigate zero-shot cross-lingual entity linking, in which we assume no bilingual lexical resources are available in the source low-resource language. Specifically, we propose pivot-based
entity linking, which leverages information from a highresource “pivot” language to train character-level neural entity linking models that are transferred to the source lowresource language in a zero-shot manner. With experiments on 9 low-resource languages and transfer through a total of
54 languages, we show that our proposed pivot-based framework improves entity linking accuracy 17% (absolute) on average over the baseline systems, for the zero-shot scenario.1 Further, we also investigate the use of language-universal phonological representations which improves average accuracy (absolute) by 36% when transferring between languages that use different scripts.
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4670/4548)
- **code**: [github](https://github.com/neulab/pivot-based-entity-linking)
- **dataset**: English Wikipedia
- **ppt/video**:
- **curator**: Xiaoyu Shang

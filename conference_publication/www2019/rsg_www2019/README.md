#  Improved Cross-Lingual Question Retrieval for Community Question Answering  
- **author**: Andreas Rücklé, Krishnkant Swarnkar, Iryna Gurevych  
- **abstract**: We perform cross-lingual question retrieval in community question answering (cQA), i.e., we retrieve similar questions for queries that are given in another language. The standard approach to cross-lingual information retrieval, which is to automatically translate the query to the target language and continue with a monolingual retrieval model, typically falls short in cQA due to translation errors. This is even more the case for specialized domains such as in technical cQA, which we explore in this work. To remedy, we propose two extensions to this approach that improve cross-lingual question retrieval: (1) we enhance an NMT model with monolingual cQA data to improve the translation quality, and (2) we improve the robustness of a state-of-the-art neural question retrieval model to common translation errors by adding back-translations during training. Our results show that we achieve substantial improvements over the baseline approach and considerably close the gap to a setup where we have access to an external commercial machine translation service (i.e., Google Translate), which is often not the case in many practical scenarios. Our source code and data is publicly available.1
- **keywords**: 
- **interpretation**: [OpenKG](https://mp.weixin.qq.com/s/76Y1gIwUm--Z0ZrooKLJpg)
- **pdf**: [paper](https://dl.acm.org/doi/10.1145/3308558.3313502)
- **code**: [github](https://github.com/UKPLab/www19-xling-question-retrieval)
- **dataset**: WMT13, WMT18
- **ppt/video**:
- **curator**: Xiaoyu Shang 

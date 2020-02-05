# Benchmarking Zero-shot Text Classification Datasets, Evaluation and Entailment Approach

- **author**:Wenpeng Yin,Jamaal Hay,Dan Roth
- **abstract**: Zero-shot text classification (0Shot-TC) is a challenging NLU problem to which little attention has been paid by the research community. 0Shot-TC aims to associate an appropriate label with a piece of text, irrespective of the text domain and the aspect (e.g., topic, emotion, event, etc.) described by the label. And there are only a few articles studying 0Shot-TC, all focusing only on topical categorization which, we argue, is just the tip of the iceberg in 0Shot-TC. In addition, the chaotic experiments in literature make no uniform comparison, which blurs the progress. 
  This work benchmarks the 0Shot-TC problem by providing unified datasets, standardized evaluations, and state-of-the-art baselines. Our contributions include: i) The datasets we provide facilitate studying 0Shot-TC relative to conceptually different and diverse aspects: the ``topic'' aspect includes ``sports'' and ``politics'' as labels; the ``emotion'' aspect includes ``joy'' and ``anger''; the ``situation'' aspect includes ``medical assistance'' and ``water shortage''. ii) We extend the existing evaluation setup (label-partially-unseen) -- given a dataset, train on some labels, test on all labels -- to include a more challenging yet realistic evaluation label-fully-unseen 0Shot-TC (Chang et al., 2008), aiming at classifying text snippets without seeing task specific training data at all. iii) We unify the 0Shot-TC of diverse aspects within a textual entailment formulation and study it this way.  
- **keywords**:
- **interpretation**:待补充
- **pdf**: [pdf](https://arxiv.org/pdf/1909.00161)
- **code**:[code](https://github.com/yinwenpeng/BenchmarkingZeroShot)
- **dataset**: studying three aspects of 0SHOT-TC: topic categorization, emotion detection, and situation frame detection
- **ppt/video**:
- **curator**: Yawen Dai
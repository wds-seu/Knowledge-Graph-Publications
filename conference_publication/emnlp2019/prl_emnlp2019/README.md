# Language Models as Knowledge Bases

- **author**:Fabio Petroni，Tim Rocktaschel， Patrick Lewis， Anton Bakhtin， Yuxiang Wu，Alexander H.Miller， Sebastian Riedel

- **abstract**: Recent progress in pretraining language models on large textual corpora led to a surge of improvements for downstream NLP tasks. Whilst learning linguistic knowledge, these models may also be storing relational knowledge present in the training data, and may be able to answer queries structured as "fill-in-the-blank" cloze statements. Language models have many advantages over structured knowledge bases: they require no schema engineering, allow practitioners to query about an open class of relations, are easy to extend to more data, and require no human supervision to train. We present an in-depth analysis of the relational knowledge already present (without fine-tuning) in a wide range of state-of-the-art pretrained language models. We find that (i) without fine-tuning, BERT contains relational knowledge competitive with traditional NLP methods that have some access to oracle knowledge, (ii) BERT also does remarkably well on open-domain question answering against a supervised baseline, and (iii) certain types of factual knowledge are learned much more readily than others by standard language model pretraining approaches. The surprisingly strong ability of these models to recall factual knowledge without any fine-tuning demonstrates their potential as unsupervised open-domain QA systems. The code to reproduce our analysis is available at [this https URL](https://github.com/facebookresearch/LAMA).  

- **keywords**:

- **interpretation**:[review](https://zhuanlan.zhihu.com/p/86604724)

- **pdf**: [pdf](https://arxiv.org/pdf/1909.01066)

- **code**: [code](https://github.com/facebookresearch/LAMA)

- **dataset**:  Google-RE dataset 

- **ppt/video**:

- **curator**: Yawen Dai
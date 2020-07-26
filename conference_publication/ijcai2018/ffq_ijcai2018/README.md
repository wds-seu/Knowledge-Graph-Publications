# Improving Low Resource Named Entity Recognition using Cross-lingual Knowledge Transfer
* **author**：Xiaocheng Feng, Xiachong Feng, Bing Qin, Zhangyin Feng, Ting Liu
* **abstract**: Neural networks have been widely used for high resource language (e.g. English) named entity recognition (NER) and have shown state-of-the-art results.However, for low resource languages, such as Dutch, Spanish, due to the limitation of resources and lack of annotated data, taggers tend to have lower performances.To narrow this gap, we propose three novel strategies to enrich the semantic representations of low resource languages: we first develop neural networks to improve low resource word representations by knowledge transfer from high resource language using bilingual lexicons. Further, a lexicon extension strategy is designed to address out-of lexicon problem by automatically learning semantic projections.Thirdly, we regard word-level entity type distribution features as an external language-independent knowledge and incorporate them into our neural architecture. Experiments on two low resource languages (including Dutch and Spanish) demonstrate the effectiveness of these additional semantic representations (average 4.8\% improvement). Moreover, on Chinese OntoNotes 4.0 dataset, our approach achieved an F-score of 83.07\% with 2.91\% absolute gain compared to the state-of-the-art results.
* **keywords**: Machine Learning: Neural Networks, Natural Language Processing: Information Extraction, Machine Learning: Deep Learning, Natural Language Processing: Named Entities
* **interpretation**: 
* **pdf**:  [link](https://www.ijcai.org/Proceedings/2018/0566.pdf)
* **code**: [link](https://github.com/scir-code/lrner)
* **dataset**: CoNLL-2002, Ontonotes 4.0
* **ppt/video**: 
* **curator**: Chang Liu

#  Named Entity Recognition as Dependency Parsing

* **author**: Juntao Yu, Bernd Bohnet, Massimo Poesio
* **abstract**: Named Entity Recognition (NER) is a fundamental task in Natural Language Processing, concerned with identifying spans of text expressing references to entities. NER research is often focused on flat entities only (flat NER), ignoring the fact that entity references can be nested, as in [Bank of [China]] (Finkel and Manning, 2009). In this paper, we use ideas from graph-based dependency parsing to provide our model a global view on the input via a biaffine model (Dozat and Manning, 2017). The biaffine model scores pairs of start and end tokens in a sentence which we use to explore all spans, so that the model is able to predict named entities accurately. We show that the model works well for both nested and flat NER through evaluation on 8 corpora and achieving SoTA performance on all of them, with accuracy gains of up to 2.2 percentage points.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2005.07150)
* **code**:[github](https://github.com/juntaoy/biaffine-ner)
* **dataset**: ACE2004,ACE2005,GENIA
* **ppt/video**:
* **curator**:Shuwei Yuan
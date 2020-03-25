# ExFaKT: A Framework for Explaining Facts over Knowledge Graphs and Text
* **author**: Mohamed H. Gad-Elrab, Daria Stepanova, Jacopo Urbani, Gerhard Weikum
* **abstract**: Fact-checking is a crucial task for accurately populating, updating and curating knowledge graphs. Manually validating candidate facts is time-consuming. Prior work on automating this task focuses on estimating truthfulness using numerical scores which are not human-interpretable. Others extract explicit mentions of the candidate fact in the text as an evidence for the candidate fact, which can be hard to directly spot. In our work, we introduce ExFaKT, a framework focused on generating human-comprehensible explanations for candidate facts. ExFaKT uses background knowledge encoded in the form of Horn clauses to rewrite the fact in question into a set of other easier-to-spot facts. The final output of our framework is a set of semantic traces for the candidate fact from both text and knowledge graphs. The experiments demonstrate that our rewritings significantly increase the recall of fact-spotting while preserving high precision. Moreover, we show that the explanations effectively help humans to perform fact-checking and can also be exploited for automating this task.
* **keywords**: Fact-checking
* **interpretation**: [来源: 专知](http://www.jintiankansha.me/t/idfJtovvD0)
* **pdf**: [link](https://dl.acm.org/doi/pdf/10.1145/3289600.3290996?download=true)
* **code**: [ExFaKT](https://www.mpi-inf.mpg.de/impact/exfakt.)
* **dataset**:YAGO-based, DBpedia-based
* **ppt/video**:
* **curation**: Jiong Zhang 
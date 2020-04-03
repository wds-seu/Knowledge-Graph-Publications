# Never-Ending Learning for Open-Domain Question Answering over Knowledge Bases  
- **author**: Abdalghani Abujabal, Rishiraj Saha Roy, Mohamed Yahya, Gerhard Weikum  
- **abstract**: Translating natural language questions to semantic representations such as SPARQL is a core challenge in open-domain question answering over knowledge bases (KB-QA). Existing methods rely on a clear separation between an offline training phase, where a model is learned, and an online phase where this model is deployed. Two major shortcomings of such methods are that (i) they require access to a large annotated training set that is not always readily available and (ii) they fail on questions from before-unseen domains. To overcome these limitations, this paper presents NEQA, a continuous learning paradigm for KB-QA. Offline, NEQA automatically learns templates mapping syntactic structures to semantic ones from a small number of training question-answer pairs. Once deployed, continuous learning is triggered on cases where templates are insufficient. Using a semantic similarity function between questions and by judicious invocation of non-expert user feedback, NEQA learns new templates that capture previously-unseen syntactic structures. This way, NEQA gradually extends its template repository. NEQA periodically re-trains its underlying models, allowing it to adapt to the language used after deployment. Our experiments demonstrate NEQA's viability, with steady improvement in answering quality over time, and the ability to answer questions from new domains.
- **keywords**: Question answering; Never-ending learning; User feedback 
- **interpretation**: 
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3178876.3186004?download=true)
- **code**:
- **dataset**: 
- **ppt/video**:
- **curator**: Xiaoyu Shang 

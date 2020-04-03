# Facet Annotation Using Reference Knowledge Bases
- **author**: Riccardo Porrini, Matteo Palmonari, Isabel F. Cruz  
- **abstract**: Faceted interfaces are omnipresent on the web to support data exploration and filtering. A facet is a triple: a domain (e.g., Book), a property (e.g., author, language), and a set of property values (e.g., Austen, Beauvoir, Coelho, Dostoevsky, Eco, Kerouac, Suskind, ..., French, English, German, Italian, Portuguese, Russian, ... ). Given a property (e.g., language), selecting one or more of its values (English and Italian) returns the domain entities (of type Book) that match the given values (the books that are written in English or Italian). To implement faceted interfaces in a way that is scalable to very large datasets, it is necessary to automate facet extraction. Prior work associates a facet domain with a set of homogeneous values, but does not annotate the facet property. In this paper, we annotate the facet property with a predicate from a reference Knowledge Base (KB) so as to maximize the semantic similarity between the property and the predicate. We define semantic similarity in terms of three new metrics: specificity, coverage, and frequency. Our experimental evaluation uses the DBpedia and YAGO KBs and shows that for the facet annotation problem, we obtain better results than a state-of-the-art approach for the annotation of web tables as modified to annotate a set of values.
- **keywords**: Facet annotation; data semantics; data lifting; table annotation; facetedsearch;eCommerce 
- **interpretation**: 
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3178876.3186020?download=true)
- **code**:
- **dataset**:  DBpedia, YAGO
- **ppt/video**:
- **curator**: Xiaoyu Shang 

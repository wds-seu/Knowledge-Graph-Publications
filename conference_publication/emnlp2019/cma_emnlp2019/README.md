# Connecting the Dots: Document-level Neural Relation Extraction with Edge-oriented Graphs 

- **author**: Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou

- **abstract**: Document-level relation extraction is a complex human process that requires logical inference to extract relationships between named entities in text. Existing approaches use graph-based neural models with words as nodes and edges as relations between them, to encode relations across sentences. These models are node-based, i.e., they form pair representations based solely on the two target node representations. However, entity relations can be better expressed through unique edge representations formed as paths between nodes. We thus propose an edge-oriented graph neural model for document-level relation extraction. The model utilises different types of nodes and edges to create a document-level graph. An inference mechanism on the graph edges enables to learn intra- and inter-sentence relations using multi-instance learning internally. Experiments on two document-level biomedical datasets for chemical-disease and gene-disease associations show the usefulness of the proposed edge-oriented approach. 

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1909.00228)

- **code**: [code](https://github.com/fenchri/edge-oriented-graph)

- **dataset**: CDR (BioCreative V),GDA (DisGeNet)

- **ppt/video**:

- **curator**: Yawen Dai
# Modelling Dynamics in Semantic Web Knowledge Graphs with Formal Concept Analysis 
- **author**: Larry González, Aidan Hogan  
- **abstract**: In this paper, we propose a novel data-driven schema for large-scale heterogeneous knowledge graphs inspired by Formal Concept Analysis (FCA). We first extract the sets of properties associated with individual entities; these property sets (aka. characteristic sets) are annotated with cardinalities and used to induce a lattice based on set-containment relations, forming a natural hierarchical structure describing the knowledge graph. We then propose an algebra over such schema lattices, which allows to compute diffs between lattices (for example, to summarise the changes from one version of a knowledge graph to another), to add lattices (for example, to project future changes), and so forth. While we argue that this lattice structure (and associated algebra) may have various applications, we currently focus on the use-case of modelling and predicting the dynamic behaviour of knowledge graphs. Along those lines, we instantiate and evaluate our methods for analysing how versions of the Wikidata knowledge graph have changed over a period of 11 weeks. We propose algorithms for constructing the lattice-based schema from Wikidata, and evaluate their efficiency and scalability. We then evaluate use of the resulting schema(ta) for predicting how the knowledge graph will evolve in future versions.
- **keywords**: Semantic Web, Schema, Knowledge Graph, Dynamics, FCA  
- **interpretation**: 
- **pdf**: [paper](http://aidanhogan.com/docs/wikidata_schema_dynamics.pdf)
- **code**: [github](https://github.com/larryjgonzalez/rdf_dynamics)
- **dataset**: Wikipedia
- **ppt/video**:
- **curator**: Xiaoyu Shang 

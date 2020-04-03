# Estimating Rule Quality for Knowledge Base Completion with the Relationship between Coverage Assumption 
- **author**: Kaja Zupanc, Jesse Davis  
- **abstract**: Currently, there are many large, automatically constructed knowledge bases (KBs). One interesting task is learning from a knowledge base to generate new knowledge either in the form of inferred facts or rules that define regularities. One challenge for learning is that KBs are necessarily open world: we cannot assume anything about the truth values of tuples not included in the KB. When a KB only contains facts (i.e., true statements), which is typically the case, we lack negative examples, which are often needed by learning algorithms. To address this problem, we propose a novel score function for evaluating the quality of a first-order rule learned from a KB. Our metric attempts to include information about the tuples not in the KB when evaluating the quality of a potential rule. Empirically, we find that our metric results in more precise predictions than previous approaches.
- **keywords**: Rule mining, Knowledge base, ILP, Open world assumption
- **interpretation**: 
- **pdf**: [paper](https://core.ac.uk/download/pdf/153429712.pdf)
- **code**:
- **dataset**: YAGO2, Wikidata, NELL 
- **ppt/video**:
- **curator**: Xiaoyu Shang 

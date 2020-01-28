# Validation of Growing Knowledge Graphs by Abductive Text Evidences 
- **author**: Jianfeng Du, Jeff Z. Pan, Sylvia Wang, Kunxun Qi, Yuming Shen, Yu Deng  
- **abstract**: This paper proposes a validation mechanism for newly added triples in a growing knowledge graph. Given a logical theory, a knowledge graph, a text corpus, and a new triple to be validated, this mechanism computes a sorted list of explanations for the new triple to facilitate the validation of it, where an explanation, called an abductive text evidence, is a set of pairs of the form (triple, window) where appending the set of triples on the left to the knowledge graph enforces entailment of the new triple under the logical theory, while every sentence window on the right which is contained in the text corpus explains to some degree why the triple on the left is true. From the angle of practice, a special class of abductive text evidences called TEP-based abductive text evidence is proposed, which is constructed from explanation patterns seen before in the knowledge graph. Accordingly, a method for computing the complete set of TEP-based abductive text evidences is proposed. Moreover, a method for sorting abductive text evidences based on distantly supervised learning is proposed. To evaluate the proposed validation mechanism, four knowledge graphs with logical theories are constructed from the four great classical masterpieces of Chinese literature. Experimental results on these datasets demonstrate the efficiency and effectiveness of the proposed mechanism.
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4130/4008)
- **code**:
- **dataset**: CNNRP, PCNNRP, CNNP, PCNNP, Rand 
- **ppt/video**:
- **curator**: Xiaoyu Shang 

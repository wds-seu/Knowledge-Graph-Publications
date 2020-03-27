# Knowledge-based Word Sense Disambiguation using Topic Models
* **author**: Devendra Singh Chaplot, Ruslan Salakhutdinov
* **abstract**: Word Sense Disambiguation is an open problem in Natural Language Processing which is particularly challenging and useful in the unsupervised setting where all the words in any given text need to be disambiguated without using any labeled data. Typically WSD systems use the sentence or a small window of words around the target word as the context for disambiguation because their computational complexity scales exponentially with the size of the context. In this paper, we leverage the formalism of topic model to design a WSD system that scales linearly with the number of words in the context. As a result, our system is able to utilize the whole document as the context for a word to be disambiguated. The proposed method is a variant of Latent Dirichlet Allocation in which the topic proportions for a document are replaced by synset proportions. We further utilize the information in the WordNet by assigning a non-uniform prior to synset distribution over words and a logistic-normal prior for document distribution over synsets. We evaluate the proposed method on Senseval-2, Senseval-3, SemEval-2007, SemEval-2013 and SemEval-2015 English All-Word WSD datasets and show that it outperforms the state-of-the-art unsupervised knowledge-based WSD system by a significant margin.
* **keywords**: Disambiguation 
* **interpretation**: [来源: BigQuant](https://bigquant.com/community/t/topic/121096)
* **pdf**: [link](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17415/16787)
* **code**: [暂无]()
* **dataset**: SensEval, SemEval
* **ppt/video**:
* **curation**: Jiong Zhang 
# Simultaneously Self-Attending to All Mentions for Full-Abstract Biological Relation Extraction
* **author**: Patrick Verga, Emma Strubell, Andrew McCallum
* **abstract**: Most work in relation extraction forms a prediction by looking at a short span of text within a single sentence containing a single entity pair mention. This approach often does not consider interactions across mentions, requires redundant computation for each mention pair, and ignores relationships expressed across sentence boundaries. These problems are exacerbated by the document- (rather than sentence-) level annotation common in biological text. In response, we propose a model which simultaneously predicts relationships between all mention pairs in a document. We form pairwise predictions over entire paper abstracts using an efficient self-attention encoder. All-pairs mention scores allow us to perform multi-instance learning by aggregating over mentions to form entity pair representations. We further adapt to settings without mention-level annotation by jointly training to predict named entities and adding a corpus of weakly labeled data. In experiments on two Biocreative benchmark datasets, we achieve state of the art performance on the Biocreative V Chemical Disease Relation dataset for models without external KB resources. We also introduce a new dataset an order of magnitude larger than existing human-annotated biological information extraction datasets and more accurate than distantly supervised alternatives.
* **keywords**: 
* **interpretation**: 
* **pdf**: [paper](https://www.aclweb.org/anthology/N18-1080.pdf)
* **code**: [github](https://github.com/patverga/bran)
* **dataset**: the Biocreative V Chemical Disease Relation benchmark (CDR), ; the Biocreative VI ChemProt benchmark (CPR), the Chemical Toxicology Database (CTD)
* **ppt/video**: 
* **curation**: Xiaoyu Shang

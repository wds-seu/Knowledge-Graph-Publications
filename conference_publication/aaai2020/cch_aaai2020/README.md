# Knowledge Graph Transfer Network for Few-Shot Recognition

* **author**: Riquan Chen, Tianshui Chen, Xiaolu Hui, Hefeng Wu, Guanbin Li, Liang Lin
* **abstract**: Few-shot learning aims to learn novel categories from very few samples given some base categories with sufficient training samples. The main challenge of this task is the novel categories are prone to dominated by color, texture, shape of the object or background context (namely specificity), which are distinct for the given few training samples but not common for the corresponding categories (see Figure 1). Fortunately, we find that transferring information of the correlated based categories can help learn the novel concepts and thus avoid the novel concept being dominated by the specificity. Besides, incorporating semantic correlations among different categories can effectively regularize this information transfer. In this work, we represent the semantic correlations in the form of structured knowledge graph and integrate this graph into deep neural networks to promote few-shot learning by a novel Knowledge Graph Transfer Network (KGTN). Specifically, by initializing each node with the classifier weight of the corresponding category, a propagation mechanism is learned to adaptively propagate node message through the graph to explore node interaction and transfer classifier information of the base categories to those of the novel ones. Extensive experiments on the ImageNet dataset show significant performance improvement compared with current leading competitors. Furthermore, we construct an ImageNet-6K dataset that covers larger scale categories, i.e, 6,000 categories, and experiments on this dataset further demonstrate the effectiveness of our proposed model.
* **keywords**:
* **intrepretation**:
* **pdf**:[link](https://arxiv.org/pdf/1911.09579)
* **code**:
* **dataset**:ImageNet-FS, ImageNet-6K
* **ppt/video**:
* **curator**:Shuwei Yuan
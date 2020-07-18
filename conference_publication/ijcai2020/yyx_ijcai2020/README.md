# Improving Knowledge Tracing via Pre-training Question Embeddings
* **author**: Yunfei Liu, Yang Yang, Xianyu Chen, Jian Shen, Haifeng Zhang, Yong Yu
* **abstract**: Knowledge tracing (KT) defines the task of predicting whether students can correctly answer questions based on their historical response. Although much research has been devoted to exploiting the question information, plentiful advanced information among questions and skills hasn't been well extracted, making it challenging for previous work to perform adequately. In this paper, we demonstrate that large gains on KT can be realized by pre-training embeddings for each question on abundant side information, followed by training deep KT models on the obtained embeddings. To be specific, the side information includes question difficulty and three kinds of relations contained in a bipartite graph between questions and skills. To pre-train the question embeddings, we propose to use product-based neural networks to recover the side information. As a result, adopting the pre-trained embeddings in existing deep KT models significantly outperforms state-of-the-art baselines on three common KT datasets.
* **keywords**: Knowledge tracing
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://www.ijcai.org/Proceedings/2020/219)
* **code**: [link](https://github.com/lyf-1/PEBG)
* **dataset**: [ASSIST09](https://sites.google.com/site/assistmentsdata/home/assistment-2009-2010-data/skill-builder-data-2009-2010), [ASSIST12](https://sites.google.com/site/assistmentsdata/home/2012-13-school-data-with-affect), [EdNet](https://github.com/riiid/ednet)
* **ppt/video**:
* **curation**: Jiong Zhang 
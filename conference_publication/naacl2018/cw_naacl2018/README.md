# KBGAN: Adversarial Learning for Knowledge Graph Embeddings
* **author**: Liwei Cai, William Yang Wang
* **abstract**: We introduce KBGAN, an adversarial learning framework to improve the performances of a wide range of existing knowledge graph embedding models. Because knowledge graphs typically only contain positive facts, sampling useful negative training examples is a nontrivial task. Replacing the head or tail entity of a fact with a uniformly randomly selected entity is a conventional method for generating negative facts, but the majority of the generated negative facts can be easily discriminated from positive facts, and will contribute little towards the training. Inspired by generative adversarial networks (GANs), we use one knowledge graph embedding model as a negative sample generator to assist the training of our desired model, which acts as the discriminator in GANs. This framework is independent of the concrete form of generator and discriminator, and therefore can utilize a wide variety of knowledge graph embedding models as its building blocks. In experiments, we adversarially train two translation-based models, TRANSE and TRANSD, each with assistance from one of the two probability-based models, DISTMULT and COMPLEX. We evaluate the performances of KBGAN on the link prediction task, using three knowledge base completion datasets: FB15k-237, WN18 and WN18RR. Experimental results show that adversarial training substantially improves the performances of target embedding models under various settings. 
* **keywords**: 
* **interpretation**: [OpenKG](https://mp.weixin.qq.com/s/E3D0t0EnQ-P4BuLYjB-5VQ)
* **pdf**: [paper](https://www.aclweb.org/anthology/N18-1133.pdf)
* **code**: [github](https://github.com/cai-lw/KBGAN)
* **dataset**: FB15k-237, WN18, WN18RR 
* **ppt/video**: [video](http://vimeo.com/277671743)
* **curation**: Xiaoyu Shang

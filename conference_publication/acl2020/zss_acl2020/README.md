#  Empower Entity Set Expansion via Language Model Probing

* **author**: Yunyi Zhang, Jiaming Shen, Jingbo Shang, Jiawei Han
* **abstract**: Entity set expansion, aiming at expanding a small seed entity set with new entities belonging to the same semantic class, is a critical task that benefits many downstream NLP and IR applications, such as question answering, query understanding, and taxonomy construction. Existing set expansion methods bootstrap the seed entity set by adaptively selecting context features and extracting new entities. A key challenge for entity set expansion is to avoid selecting ambiguous context features which will shift the class semantics and lead to accumulative errors in later iterations. In this study, we propose a novel iterative set expansion framework that leverages automatically generated class names to address the semantic drift issue. In each iteration, we select one positive and several negative class names by probing a pre-trained language model, and further score each candidate entity based on selected class names. Experiments on two datasets show that our framework generates high-quality class names and outperforms previous state-of-the-art methods significantly.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/2004.13897)
* **code**:[github](https://github.com/yzhan238/CGExpan)
* **dataset**:WiKi,APR
* **ppt/video**:
* **curator**:Shuwei Yuan


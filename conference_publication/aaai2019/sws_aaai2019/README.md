# Amalgamating Knowledge towards Comprehensive Classification 
- **author**: Chengchao Shen, Xinchao Wang, Jie Song, Li Sun, Mingli Song    
- **abstract**: With the rapid development of deep learning, there have been an unprecedentedly large number of trained deep network models available online. Reusing such trained models can significantly reduce the cost of training the new models from scratch, if not infeasible at all as the annotations used for the training original networks are often unavailable to public. We propose in this paper to study a new model-reusing task, which we term as knowledge amalgamation. Given multiple trained teacher networks, each of which specializes in a different classification problem, the goal of knowledge amalgamation is to learn a lightweight student model capable of handling the comprehensive classification. We assume no other annotations except the outputs from the teacher models are available, and thus focus on extracting and amalgamating knowledge from the multiple teachers. To this end, we propose a pilot two-step strategy to tackle the knowledge amalgamation task, by learning first the compact feature representations from teachers and then the network parameters in a layer-wise manner so as to build the student model. We apply this approach to four public datasets and obtain very encouraging results: even without any human annotation, the obtained student model is competent to handle the comprehensive classification task and in most cases outperforms the teachers in individual sub-tasks.
- **keywords**: 
- **interpretation**: 
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4165/4043)
- **code**: 
- **dataset**: CUB-2002011 (Wah et al. 2011), Stanford Dogs (Khosla et al. 2011), FGVCAircraft(Majietal.2013), Cars(Krauseetal.2013)
- **ppt/video**: 
- **curator**: Xiaoyu Shang 

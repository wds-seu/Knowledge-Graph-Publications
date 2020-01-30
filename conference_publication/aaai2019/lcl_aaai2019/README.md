# Exploiting the Ground-Truth: An Adversarial Imitation Based Knowledge Distillation Approach for Event Detection 
- **author**: Jian Liu, Yubo Chen, Kang Liu     
- **abstract**: The ambiguity in language expressions poses a great challenge for event detection. To disambiguate event types, current approaches rely on external NLP toolkits to build knowledge representations. Unfortunately, these approaches work in a pipeline paradigm and suffer from error propagation problem. In this paper, we propose an adversarial imitation based knowledge distillation approach, for the first time, to tackle the challenge of acquiring knowledge from rawsentences for event detection. In our approach, a teacher module is first devised to learn the knowledge representations from the ground-truth annotations. Then, we set up a student module that only takes the raw-sentences as the input. The student module is taught to imitate the behavior of the teacher under the guidance of an adversarial discriminator. By this way, the process of knowledge distillation from rawsentence has been implicitly integrated into the feature encoding stage of the student module. To the end, the enhanced student is used for event detection, which processes raw texts and requires no extra toolkits, naturally eliminating the error propagation problem faced by pipeline approaches. We conduct extensive experiments on the ACE 2005 datasets, and the experimental results justify the effectiveness of our approach.   
- **keywords**: 
- **interpretation**:
- **pdf**: [paper](https://www.aaai.org/ojs/index.php/AAAI/article/view/4649/4527)
- **code**: 
- **dataset**: ACE2005 
- **ppt/video**:
- **curator**: Xiaoyu Shang

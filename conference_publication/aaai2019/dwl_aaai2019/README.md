# Triple Classification Using Regions and Fine-Grained Entity Typing  
- **author**: Tiansi Dong, Zhigang Wang, Juanzi Li, Christian Bauckhage, Armin B.Cremers    
- **abstract**: A Triple in knowledge-graph takes a form that consists of head, relation, tail. Triple Classification is used to determine the truth value of an unknown Triple. This is a hard task for 1-to-N relations using the vector-based embedding approach. We propose a new region-based embedding approach using fine-grained type chains. A novel geometric process is presented to extend the vectors of pre-trained entities into n-balls (n-dimensional balls) under the condition that head balls shall contain their tail balls. Our algorithm achieves zero energy cost, therefore, serves as a case study of perfectly imposing tree structures into vector space. An unknown Triple (h,r,x) will be predicted as true, when x’s n-ball is located in the r-subspace of h’s n-ball, following the same construction of known tails of h. The experiments are based on large datasets derived from the benchmark datasets WN11, FB13, and WN18. Our results show that the performance of the new method is related to the length of the type chain and the quality of pre-trained entityembeddings, and that performances of long chains with welltrained entity-embeddings outperform other methods in the literature. Source codes and datasets are located at https: //github.com/GnodIsNait/mushroom.  
- **keywords**: 
- **interpretation**:
- **pdf**: [paper](https://aaai.org/ojs/index.php/AAAI/article/view/3771)
- **code**: [github](https://github.com/GnodIsNait/mushroom)
- **dataset**: WordNet, Freebase 
- **ppt/video**:
- **curator**: Xiaoyu Shang 

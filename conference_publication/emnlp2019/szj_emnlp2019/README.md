# A Progressive Model to Enable Continual Learning for Semantic Slot Filling

- **author**:Yilin Shen,Xiangyu Zeng,Hongxia Jin
- **abstract**:Semantic slot filling is one of the major tasks in spoken language understanding (SLU). After a slot filling model is trained on precollected data, it is crucial to continually improve the model after deployment to learn users’ new expressions. As the data amount grows, it becomes infeasible to either store such huge data and repeatedly retrain the model on all data or fine tune the model only on new data without forgetting old expressions. In this paper, we introduce a novel progressive slot filling model, ProgModel. ProgModel consists of a novel context gate that transfers previously learned knowledge to a small size expanded component; and meanwhile enables this new component to be fast trained to learn from new data. As such, ProgModel learns the new knowledge by only using new data at each time and meanwhile preserves the previously learned expressions. Our experiments show that ProgModel needs much less training time and smaller model size to outperform various model fine tuning competitors by up to 4.24% and 3.03% on two benchmark datasets. 
- **keywords**:
- **interpretation**:待补充
- **pdf**: [pdf](https://www.aclweb.org/anthology/D19-1126.pdf)
- **code**: 
- **dataset**:ATIS,Snips dataset
- **ppt/video**:
- **curator**: Yawen Dai
# Diachronic Embedding for Temporal Knowledge Graph Completion

* **author**: Rishab Goel, Seyed Mehran Kazemi, Marcus Brubaker, Pascal Poupart
* **abstract**:Knowledge graphs (KGs) typically contain temporal facts indicating relationships among entities at different times. Due to their incompleteness, several approaches have been proposed to infer new facts for a KG based on the existing ones-a problem known as KG completion. KG embedding approaches have proved effective for KG completion, however, they have been developed mostly for static KGs. Developing temporal KG embedding models is an increasingly important problem. In this paper, we build novel models for temporal KG completion through equipping static models with a diachronic entity embedding function which provides the characteristics of entities at any point in time. This is in contrast to the existing temporal KG embedding approaches where only static entity features are provided. The proposed embedding function is model-agnostic and can be potentially combined with any static model. We prove that combining it with SimplE, a recent model for static KG embedding, results in a fully expressive model for temporal KG completion. Our experiments indicate the superiority of our proposal compared to existing baselines.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1907.03143)
* **code**:[github](https://github.com/BorealisAI/de-simple)
* **dataset**:TKGC:ICEWS,GDELT
* **ppt/video**:
* **curator**:Shuwei Yuan
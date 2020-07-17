# A Novel Cascade Binary Tagging Framework for Relational Triple Extraction

* **author**: Zhepei Wei, Jianlin Su, Yue Wang, Yuan Tian, Yi Chang
* **abstract**: Extracting relational triples from unstructured text is crucial for large-scale knowledge graph construction. However, few existing works excel in solving the overlapping triple problem where multiple relational triples in the same sentence share the same entities. In this work, we introduce a fresh perspective to revisit the relational triple extraction task and propose a novel cascade binary tagging framework (CasRel) derived from a principled problem formulation. Instead of treating relations as discrete labels as in previous works, our new framework models relations as functions that map subjects to objects in a sentence, which naturally handles the overlapping problem. Experiments show that the CasRel framework already outperforms state-of-the-art methods even when its encoder module uses a randomly initialized BERT encoder, showing the power of the new tagging framework. It enjoys further performance boost when employing a pre-trained BERT encoder, outperforming the strongest baseline by 17.5 and 30.2 absolute gain in F1-score on two public datasets NYT and WebNLG, respectively. In-depth analysis on different scenarios of overlapping triples shows that the method delivers consistent performance gain across all these scenarios. The source code and data are released online.
* **keywords**:
* **interpretation**:
* **pdf**:[link](https://arxiv.org/pdf/1909.03227)
* **code**:[github](https://github.com/weizhepei/CasRel)
* **dataset**:NYT,WebNLG,ACE04,NYT10-HRL,NYT11-HRL,Wiki-KBP
* **ppt/video**:
* **curator**:Shuwei Yuan


## Learning Named Entity Tagger using Domain-Specific Dictionary

**author**:Jingbo Shang, Liyuan Liu, Xiaotao Gu, Xiang Ren, Teng Ren, Jiawei Han

**abstract**:Recent advances in deep neural models allow us to build reliable named entity recognition
(NER) systems without handcrafting features. However, such methods require large amounts of manually-labeled training data. There have been efforts on replacing human annotations with distant supervision (in conjunction with external dictionaries), but the generated noisy labels pose significant challenges on learning effective neural models. Here we propose
two neural models to suit noisy distant supervision from the dictionary. First, under the traditional sequence labeling framework, we propose a revised fuzzy CRF layer to handle tokens with multiple possible labels. After identifying the nature of noisy labels in distant supervision, we go beyond the traditional
framework and propose a novel, more effective neural model AutoNER with a new Tie or Break scheme. In addition, we discuss how to refine distant supervision for better NER performance. Extensive experiments
on three benchmark datasets demonstrate that AutoNER achieves the best performance when only using dictionaries with no additional human effort, and delivers competitive results with state-of-the-art supervised benchmarks.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1230.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
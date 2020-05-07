## Indirect Supervision for Relation Extraction using Question-Answer Pairs

**author**:Zeqiu Wu,Xiang Ren,Frank F.Xu,Ji Li,Jiawei Han

<<<<<<< HEAD
**abstract**:Automatic relation extraction (RE) for types of interest is of great importance for interpreting massive text corpora in an efficient manner. For example, we want to identify the relationship “president_of” between entities “Donald Trump” and “United States” in a sentence expressing such a relation. Traditional RE models have heavily relied on human-annotated corpus for training, which can be costly in generating labeled data and become obstacles when dealing with more relation types. Thus, more RE extraction systems have shifted to be built upon training data automatically acquired by linking to
knowledge bases (distant supervision). However, due to the incompleteness of knowledge bases and the context-agnostic labeling, the training data collected via distant supervision (DS) can be very noisy. In recent years, as increasing attention has been brought to
tackling question-answering (QA) tasks, user feedback or datasets of such tasks become more accessible. In this paper, we propose a novel framework, ReQuest, to leverage question-answer pairs as an indirect source of supervision for relation extraction, and study how to use such supervision to reduce noise induced from
DS. Our model jointly embeds relation mentions, types, QA entity mention pairs and text features in two low-dimensional spaces (RE and QA), where objects with same relation types or semantically similar question-answer pairs have similar representations. Shared features connect these two spaces, carrying clearer semantic
knowledge from both sources. ReQuest, then use these learned embeddings to estimate the types of test relation mentions. We formulate a global objective function and adopt a novel margin-based QA loss to reduce noise in DS by exploiting semantic evidence from
=======
**abstract**:Automatic relation extraction (RE) for types of interest is of great importance for interpreting massive text corpora in an efficient manner. For example, we want to identify the relationship “president_of” between entities “Donald Trump” and “United States” in a sentence expressing such a relation. Traditional RE models have heavily relied on human-annotated corpus for training, which can be costly in generating labeled data and become obstacles when dealing with more relation types. Thus, more RE extraction systems have shifted to be built upon training data automatically acquired by linking to
knowledge bases (distant supervision). However, due to the incompleteness of knowledge bases and the context-agnostic labeling, the training data collected via distant supervision (DS) can be very noisy. In recent years, as increasing attention has been brought to
tackling question-answering (QA) tasks, user feedback or datasets of such tasks become more accessible. In this paper, we propose a novel framework, ReQuest, to leverage question-answer pairs as an indirect source of supervision for relation extraction, and study how to use such supervision to reduce noise induced from
DS. Our model jointly embeds relation mentions, types, QA entity mention pairs and text features in two low-dimensional spaces (RE and QA), where objects with same relation types or semantically similar question-answer pairs have similar representations. Shared features connect these two spaces, carrying clearer semantic
knowledge from both sources. ReQuest, then use these learned embeddings to estimate the types of test relation mentions. We formulate a global objective function and adopt a novel margin-based QA loss to reduce noise in DS by exploiting semantic evidence from
>>>>>>> f7f865ca8de4bb7911d0c29a767aa113c7dc7243
the QA dataset. Our experimental results achieve an average of 11% improvement in F1 score on two public RE datasets combined with TREC QA dataset. Codes and datasets can be downloaded at https://github.com/ellenmellon/ReQuest.

**keywords**:

**interpretation**:

**pdf**:[paper](https://dl.acm.org/doi/10.1145/3159652.3159709)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
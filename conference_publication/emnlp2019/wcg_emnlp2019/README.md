#  Investigating BERT's Knowledge of Language: Five Analysis Methods with NPIs 

- **author**:Alex Warstadt,  Yu Cao,  Ioana Grosu, Wei Peng, Hagen Blix,  Yining Nie, Anna Alsop,  Shikha Bordia,  Haokun Liu, Alicia Parrish, Sheng-Fu Wang, Jason Phang, Anhad Mohananey,  Phu Mon Htut, Paloma Jeretic,Samuel R.Bowman

- **abstract**: Though state-of-the-art sentence representation models can perform tasks requiring significant knowledge of grammar, it is an open question how best to evaluate their grammatical knowledge. We explore five experimental methods inspired by prior work evaluating pretrained sentence representation models. We use a single linguistic phenomenon, negative polarity item (NPI) licensing in English, as a case study for our experiments. NPIs like "any" are grammatical only if they appear in a licensing environment like negation ("Sue doesn't have any cats" vs. "Sue has any cats"). This phenomenon is challenging because of the variety of NPI licensing environments that exist. We introduce an artificially generated dataset that manipulates key features of NPI licensing for the experiments. We find that BERT has significant knowledge of these features, but its success varies widely across different experimental methods. We conclude that a variety of methods is necessary to reveal all relevant aspects of a model's grammatical knowledge in a given domain.  

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://arxiv.org/pdf/1909.02597)

- **code**: [code](https://github.com/nyu-mll/jiant/tree/blimp-and-npi/scripts/bert_npi)

- **dataset**:CoLA

- **ppt/video**:

- **curator**: Yawen Dai
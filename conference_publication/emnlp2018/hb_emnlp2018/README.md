## Decoupling Structure and Lexicon for Zero-Shot Semantic Parsing

**author**:Jonathan Herzig,Jonathan Berant

**abstract**:Building a semantic parser quickly in a new domain is a fundamental challenge for conversational interfaces, as current semantic parsers
require expensive supervision and lack the ability to generalize to new domains. In this paper, we introduce a zero-shot approach to semantic parsing that can parse utterances in unseen domains while only being trained on examples in other source domains. First, we map an utterance to an abstract, domainindependent, logical form that represents the structure of the logical form, but contains slots instead of KB constants. Then, we replace slots with KB constants via lexical alignment scores and global inference. Our model reaches an average accuracy of 53.4% on 7 domains in the OVERNIGHT dataset, substantially better than other zero-shot baselines, and performs as good as a parser trained on over 30% of the target domain examples.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1190.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
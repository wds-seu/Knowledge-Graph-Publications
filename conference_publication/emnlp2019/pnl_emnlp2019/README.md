# Knowledge Enhanced Contextual Word Representations

- **author**:Matthew E.Peters,Mark Neumann,Robert L.Logan IV,Roy Schwartz, Vidur Joshi,Sameer Singh, Noah A.Smith

- **abstract**: Contextual word representations, typically trained on unstructured, unlabeled text, do not contain any explicit grounding to real world entities and are often unable to remember facts about those entities. We propose a general method to embed multiple knowledge bases (KBs) into large scale models, and thereby enhance their representations with structured, human-curated knowledge. For each KB, we first use an integrated entity linker to retrieve relevant entity embeddings, then update contextual word representations via a form of word-to-entity attention. In contrast to previous approaches, the entity linkers and self-supervised language modeling objective are jointly trained end-to-end in a multitask setting that combines a small amount of entity linking supervision with a large amount of raw text. After integrating WordNet and a subset of Wikipedia into BERT, the knowledge enhanced BERT (KnowBert) demonstrates improved perplexity, ability to recall facts as measured in a probing task and downstream performance on relationship extraction, entity typing, and word sense disambiguation. KnowBert's runtime is comparable to BERT's and it scales to large KBs.  

- **keywords**:

- **interpretation**:[review](https://blog.csdn.net/Kaiyuan_sjtu/article/details/102857555)

- **pdf**: [pdf](https://arxiv.org/pdf/1909.04164)

- **code**: 

- **dataset**:AIDA-CoNLL

- **ppt/video**:

- **curator**: Yawen Dai
# Data-Efficient Goal-Oriented Conversation with Dialogue Knowledge Transfer Networks

- **author**: Igor Shalyminov, Sungjin Lee, Arash Eshghi, Oliver Lemon
- **abstract**: Goal-oriented dialogue systems are now being widely adopted in industry where it is of key importance to maintain a rapid prototyping cycle for new products and domains. Data-driven dialogue system development has to be adapted to meet this requirement --- therefore, reducing the amount of data and annotations necessary for training such systems is a central research problem. 
  In this paper, we present the Dialogue Knowledge Transfer Network (DiKTNet), a state-of-the-art approach to goal-oriented dialogue generation which only uses a few example dialogues (i.e. few-shot learning), none of which has to be annotated. We achieve this by performing a 2-stage training. Firstly, we perform unsupervised dialogue representation pre-training on a large source of goal-oriented dialogues in multiple domains, the MetaLWOz corpus. Secondly, at the transfer stage, we train DiKTNet using this representation together with 2 other textual knowledge sources with different levels of generality: ELMo encoder and the main dataset's source domains. 
  Our main dataset is the Stanford Multi-Domain dialogue corpus. We evaluate our model on it in terms of BLEU and Entity F1 scores, and show that our approach significantly and consistently improves upon a series of baseline models as well as over the previous state-of-the-art dialogue generation model, ZSDG. The improvement upon the latter --- up to 10% in Entity F1 and the average of 3% in BLEU score --- is achieved using only the equivalent of 10% of ZSDG's in-domain training data. 
- **keywords**:
- **interpretation**:
- **pdf**: [pdf](https://arxiv.org/pdf/1910.01302)
- **code**: 
- **dataset**: Stanford Multi-Domain (SMD) dialogue dataset
- **ppt/video**:
- **curator**: Yawen Dai
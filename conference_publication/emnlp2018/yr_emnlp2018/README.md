## TWOWINGOS: A Two-Wing Optimization Strategy for Evidential Claim Verification
**author**:Wenpeng Yin,Dan Roth

**abstract**:Determining whether a given claim is supported by evidence is a fundamental NLP problem that is best modeled as Textual Entailment. However, given a large collection of text, finding evidence that could support or refute a given claim is a challenge in itself, amplified by the fact that different evidence might be needed to support or refute a claim. Nevertheless, most prior work decouples evidence
identification from determining the truth value
of the claim given the evidence. We propose to consider these two aspects jointly. We develop TWOWINGOS (twowing optimization strategy), a system that, while identifying appropriate evidence for a claim, also determines whether or not the claim is supported by the evidence. Given the claim, TWOWINGOS attempts to identify a subset of the evidence candidates; given the predicted evidence, it then attempts to determine the truth value of the corresponding claim. We treat this challenge as coupled optimization problems, training a joint model for it. TWOWINGOS offers two advantages: (i) Unlike pipeline systems, it facilitates flexible-size evidence set, and (ii) Joint training improves both the claim verification and the evidence identification. Experiments on a benchmark dataset show state-of-the-artperformance.

**keywords**:

**interpretation**:

**pdf**:[paper](https://www.aclweb.org/anthology/D18-1010.pdf)

**code**:

**dataset**:

**ppt/video**:

**curator**:Ranran Chu
# **Personalized Knowledge Graph Summarization: From the Cloud to Your Pocket**

- **author**:Tara Safavi, Caleb Belth, Lukas Faber, Davide Mottin, Emmanuel Müller, Danai Koutra:

- **abstract**: The increasing scale of encyclopedic knowledge graphs (KGs) calls for summarization as a way to help users efficiently access and distill world knowledge. Motivated by the disparity between individuals' limited information needs and the massive scale of KGs, in this paper we propose a new problem called personalized knowledge graph summarization. The goal is to construct compact "personal summaries" of KGs containing only the facts most relevant to individuals' interests. Such summaries can be stored and utilized on-device, allowing individuals private, anytime access to the information that interests them most. We formalize the problem as one of constructing a sparse graph, or summary, that maximizes a user's inferred "utility" over a given KG, subject to a user-and device-specific constraint on the summary's size. To solve it, we propose GLIMPSE, a summarization framework that provides theoretical guarantees on the summary's utility and is linear in the number of edges in the KG. In an evaluation with real user queries to open-source, encyclopedic KGs of up to one billion triples, we show that GLIMPSE efficiently creates summaries that outperform strong baselines by up to 19% in query answering F1 score.

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](https://www.semanticscholar.org/paper/Personalized-Knowledge-Graph-Summarization%3A-From-to-Safavi-Belth/e469a28ab7379bf892fcd5955b964178b169b0f3)

- **code**: [code](https://github.com/tsafavi/glimpse-summary)

- **dataset**: DBPedia3.5.1，YAGO3,Freebase

- **ppt/video**:

- **curator**:Shuwei Yuan
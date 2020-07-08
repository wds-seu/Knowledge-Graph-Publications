# Maverick: Discovering Exceptional Facts from Knowledge Graphs

- **author**:  Gensheng Zhang,  Damian Jimenez，Chengkai Li.
- **abstract**: This paper presents Maverick, a system for discovering exceptional facts about entities in knowledge graphs. Maverick is built upon a beam-search based algorithmic framework which we proposed in a research paper that is published in SIGMOD 2018. In this demonstration proposal, we showcase an end-to-end system that includes a user-facing portal and a cache server. In Maverick, an exceptional fact about an entity of interest is modeled as a contextsubspace pair, in which the subspace is a set of attributes and the context is defined by a graph query pattern of which the entity is a match, together with other matching entities. The entity is exceptional among the entities in the context, with regard to the subspace. The portal allows users to search entities in a knowledge graph and explores exceptional facts about the entities of interest. It presents exceptional facts to users in forms of natural language sentences and illustration charts, for better interpretability of the discovered exceptional facts. The cache server stores intermediate computation results, such as pattern evaluations, exceptionality calculations, and candidate patterns. It is built for sharing computation across entities, such that repetitive computation across entities can be avoided.
- **keywords**: Discover  facts ，Knowledge graphs
- **interpretation**:
- **pdf**: [paper](http://www.vldb.org/pvldb/vol11/p1934-zhang.pdf)
- **code**: 
- **dataset**: Film and FIFA World Cup
- **ppt/video**:
- **curator**: Jidong He

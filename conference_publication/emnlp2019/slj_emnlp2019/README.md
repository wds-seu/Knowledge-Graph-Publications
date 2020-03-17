# Cross-lingual Structure Transfer for Relation and Event Extraction

- **author**: Ananya Subburathinam, Di Lu , Heng Ji, Jonathan May, Shih-Fu Chang, Avirup Sil, Clare Voss 

- **abstract**: The identification of complex semantic struc-tures such as events and entity relations, al-ready a challenging Information Extractiontask, is doubly difficult from sources writtenin under-resourced and under-annotated lan-guages. Weinvestigatethesuitabilityofcross-lingual structure transfer techniques for thesetasks. We exploit relation- and event-relevantlanguage-universal features, leveraging bothsymbolic(includingpart-of-speechanddepen-dency path) and distributional (including typerepresentation and contextualized representa-tion) information. By representing all entitymentions, event triggers, and contexts into thiscomplex and structured multilingual commonspace,usinggraphconvolutionalnetworks,wecan train a relation or event extractor fromsource language annotations and apply it tothe target language. Extensive experimentson cross-lingual relation and event transferamong English, Chinese, and Arabic demon-strate that our approach achieves performancecomparabletostate-of-the-artsupervisedmod-els trained on up to 3,000 manually annotatedmentions: up to 62.6% F-score for RelationExtraction, and 63.1% F-score for Event Ar-gument Role Labeling. The event argumentrole labeling model transferred from EnglishtoChineseachievessimilarperformanceasthemodel trained from Chinese. We thus findthat language-universal symbolic and distribu-tional representations are complementary forcross-lingual structure transfer.

- **keywords**:

- **interpretation**:

- **pdf**: [pdf](http://nlp.cs.rpi.edu/paper/crosslingualstructure2019.pdf)

- **code**:

- **dataset**: Arabic and Chinese test datasets

- **ppt/video**:

- **curator**: Yawen Dai
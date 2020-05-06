#Towards Practical Open Knowledge Base Canonicalization.. 
- **author**:	Tien-Hsuan Wu, Zhiyong Wu, Ben Kao, Pengcheng Yin
- **abstract**:An Open Information Extraction (OIE) system processes textual data to extract assertions, which are structured data typically represented in the form of (subject;relation; object) triples. An Open Knowledge Base (OKB) is a collection of such assertions. We study the problem of canonicalizing an OKB, which is defined as the problem of mapping each name (a textual term such as "the rockies", "colorado rockies") to a canonical form (such as "rockies"). Galárraga et al. [18] proposed a hierarchical agglomerative clustering algorithm using canopy clustering to tackle the canonicalization problem. The algorithm was shown to be very effective. However, it is not efficient enough to practically handle large OKBs due to the large number of similarity score computations. We propose the FAC algorithm for solving the canonicalization problem. FAC employs pruning techniques to avoid unnecessary similarity computations, and bounding techniques to efficiently approximate and identify small similarities. In our experiments, FAC registers ordersof-magnitude speedups over other approaches.
- **keywords**: Entity Resolution; Open Knowledge Base; Canonicalization
- **interpretation**:
- **pdf**: [paper](https://dl.acm.org/doi/pdf/10.1145/3269206.3271707)
- **code**: 
- **dataset**: 
- **ppt/video**:
- **curator**: Wu Bo
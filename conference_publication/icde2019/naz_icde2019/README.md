# Fine-Grained Provenance for Matching & ETL
* **author**: Nan Zheng, Abdussalam Alawini, Zachary G. Ives
* **abstract**: Data provenance tools capture the steps used to produce analyses. However, scientists must choose among workflow provenance systems, which allow arbitrary code but only track provenance at the granularity of files; provenance APIs, which provide tuple-level provenance, but incur overhead in all computations; and database provenance tools, which track tuple-level provenance through relational operators and support optimization, but support a limited subset of data science tasks. None of these solutions are well suited for tracing errors introduced during common ETL, record alignment, and matching tasks - for data types such as strings, images, etc. Scientists need new capabilities to identify the sources of errors, find why different code versions produce different results, and identify which parameter values affect output. We propose PROVision, a provenance-driven troubleshooting tool that supports ETL and matching computations and traces extraction of content within data objects. PROVision extends database-style provenance techniques to capture equivalences, support optimizations, and enable selective evaluation. We formalize our extensions, implement them in the PROVision system, and validate their effectiveness and scalability for common ETL and matching tasks.
* **keywords**: data provenance
* **interpretation**: [来源: 暂无]()
* **pdf**: [link](https://ieeexplore.ieee.org/document/8731460/)
* **code**: 
* **dataset**:
* **ppt/video**:
* **curation**: Jiong Zhang 
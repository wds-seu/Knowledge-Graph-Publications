## 论文整理中的注意事项和约定

### 约定

* 仅整理顶会中已录用的知识图谱相关论文，非顶会论文不考虑；
* 什么样的论文是“与知识图谱相关的”？标准：
  * 标题或摘要中出现了"knowledge Graph",或：
  * 虽未直接提到"knowledge Graph"，但标题或摘要中出现了"knowledge"，在正文中提到"linked data"或"knowledge base"；
  * 整理人员需要对论文的主题进行一定主观判断，判断其是否以"knowledge"为主题，还是仅仅提到了"knowledge"（例如在相关工作中），这类文章可以丢弃。
* 为每个会议在`conference_publication/`目录下建一个单独的目录，例如AAAI2019建立在`conference_publication/aaai2019/`，AAAI2018建立在`conference_publication/aaai2018/`。在每个会议目录中建立README.md，在其中罗列该次会议中所有与知识图谱相关的论文（按照论文所在的track进行组织）。
* 为每篇论文在对应的会议目录中单独建立一个目录，目录名为:"前三个作者姓氏首字母拼接+"_"+会议名"，例如AAAI2019的论文"Entity Alignment between Knowledge Graphs Using Attribute Embeddings",作者为

-当无法通过某个会议的官网找到accepted paper的时候，可以通过DBLP来查找，例如[AAAI2019的论文](https://dblp.uni-trier.de/db/conf/aaai/aaai2019.html)，而且DBLP还能罗列出每篇论文所在的track；
- 

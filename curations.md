## 论文整理中的注意事项和约定

### 约定

* 仅整理顶会中已录用的知识图谱相关论文，非顶会论文不考虑；
* 什么样的论文是“与知识图谱相关的”？标准：
  * 标题或摘要中出现了"knowledge Graph",或：
  * 虽未直接提到"knowledge Graph"，但标题或摘要中出现了"knowledge"，在正文中提到"linked data"或"knowledge base"；
  * 整理人员需要对论文的主题进行一定主观判断，判断其是否以"knowledge"为主题，还是仅仅提到了"knowledge"（例如在相关工作中），这类文章可以丢弃。
* 为每个会议在`conference_publication/`目录下建一个单独的目录，例如AAAI2019建立在`conference_publication/aaai2019/`，AAAI2018建立在`conference_publication/aaai2018/`。在每个会议目录中建立README.md，在其中罗列该次会议中所有与知识图谱相关的论文（按照论文所在的track进行组织）。
* 为每篇论文在对应的会议目录中单独建立一个目录，目录名为:"前三个作者姓氏首字母拼接+下划线+会议名"，例如AAAI2019的论文"Entity Alignment between Knowledge Graphs Using Attribute Embeddings",作者为Jianfeng Du, Jeff Z. Pan, Sylvia Wang...，则该论文的目录名为`conference_publication/aaai2019/dpw_aaai2019`,注意：只取前三位作者的姓氏首字母，不足三人就按实际人数，如果出现重名则命名为dpw1_aaai2019或dpw2_aaai2019。
* 在每篇论文的目录内建立README.md,其内容包括（以XXX为基本模板）：
 * 论文标题
 * 论文作者
 * 整理人员的姓名拼音（名在前，姓在后），例如：curator: Xiang Zhang
  * 论文解读文章的链接（review page）
  * 论文PDF链接
  * 关键词（论文中一般会给出）
  * 摘要
  * 论文的源码
  * 论文现场报告的video或ppt
  * 论文的实验数据集名称
* 论文的源码、video、ppt和实验数据集名称可以留空，等待在讨论班报告该论文的同学填入。

### 注意事项

* 当无法通过某个会议的官网找到accepted paper的时候，可以通过DBLP来查找，例如[AAAI2019的论文](https://dblp.uni-trier.de/db/conf/aaai/aaai2019.html)，而且DBLP还能罗列出每篇论文所在的track；
* 利用谷歌常常可以搜索到一些解读顶会论文的文章，比如PaperWeekly、新智元、机器之心等等；
* 利用谷歌学术可以找到大部分论文的PDF链接；

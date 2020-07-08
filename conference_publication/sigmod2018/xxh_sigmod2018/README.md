# When Query Authentication Meets Fine-Grained Access Control: A Zero-Knowledge Approach

- **author**:  Cheng Xu，Jianliang Xu，Haibo Hu，Man Ho Au
- **abstract**: Query authentication has been extensively studied to ensure the integrity of query results for outsourced databases, which are often not fully trusted. However, access control, another important security concern, is largely ignored by existing works. Notably, recent breakthroughs in cryptography have enabled fine-grained access control over outsourced data. In this paper, we take the first step toward studying the problem of authenticating relational queries with fine-grained access control. The key challenge is how to protect information confidentiality during query authentication, which is essential to many critical applications. To address this challenge, we propose a novel access-policy-preserving (APP) signature as the primitive authenticated data structure. A useful property of the APP signature is that it can be used to derive customized signatures for unauthorized users to prove the inaccessibility while achieving the zero-knowledge confidentiality. We also propose a grid-index-based tree structure that can aggregate APP signatures for efficient range and join query authentication. In addition to this, a number of optimization techniques are proposed to further improve the authentication performance. Security analysis and performance evaluation show that the proposed solutions and techniques are robust and efficient under various system settings.
- **keywords**: Query processing; Data integrity; Fine-grained access control
- **interpretation**:
- **pdf**: [paper](https://www.researchgate.net/publication/325375433_When_Query_Authentication_Meets_Fine-Grained_Access_Control_A_Zero-Knowledge_Approach)
- **code**: 
- **dataset**: 
- **ppt/video**:
- **curator**: Jidong He

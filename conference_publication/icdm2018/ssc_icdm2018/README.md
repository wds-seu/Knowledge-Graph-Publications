# Demographic Inference Via Knowledge Transfer in Cross-Domain Recommender Systems

- **author**: Jin Shang , Mingxuan Sun , Kevyn Collins-Thompson  
- **abstract**:  User demographics such as age and gender are very useful in recommender systems for applications such as personalization services and marketing, but may not always be available for individual users. Existing approaches can infer users' private demographics based on ratings, given labeled data from users who share demographics. However, such labeled information is not always available in many e-commerce services, particularly small online retailers and most media sites, for which no user registration is required. We introduce a novel probabilistic matrix factorization model for demographic transfer that enables knowledge transfer from the source domain, in which users' ratings and the corresponding demographics are available, to the target domain, in which we would like to infer unknown user demographics from ratings. Our proposed method is based on two observations: (1) Items from different but related domains may share the same latent factors such as genres and styles, and (2) Users who share similar demographics are likely to prefer similar genres across domains. This approach can align latent factors across domains that share neither common users nor common items, associating user demographics with latent factors in a unified framework. Experiments on cross-domain datasets demonstrate that the proposed method consistently improves demographic classification accuracy over existing methods. 
- **keywords**: Demographic inference, Recommender systems, Matrix factorization
- **interpretation**:
- **pdf**: [pdf](https://jshang2.github.io/pubs/crossdemo.pdf)
- **code**: 
- **dataset**:MovieLens, Flixster, BookCrossing
- **ppt/video**:
- **curator**: Yawen Dai

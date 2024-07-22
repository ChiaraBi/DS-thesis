# Word2Box: Analysis and exploration of a geometric word embedding algorithm

### Abstract

Vector word embeddings are powerful tools, but they do not naturally express uncertainty about the target concept. Furthermore, they do not naturally model asymmetric relations since they are compared using symmetric distance functions, such as dot product, cosine similarity, or Euclidean distance. This has led to exploring new ways of representing words based on Geometric Representations. Word2Box is a geometric extension of Word2Vec that learns region-based word representations that allow to perform set-theoretic operations between words. In fact, it is a fuzzy set interpretation of box embeddings, where each word is represented by an n-dimensional hyperrectangle, also called ”box”. This innovative approach enables modelling uncertainty and asymmetric relationships between words, offering a significant improvement over traditional vector embeddings. By leveraging the properties of fuzzy sets and geometric shapes, WordzBox provides a more nuanced and flexible representation of word meanings, allowing to capture complex linguistic relationships that cannot be represented with point-based embeddings. This thesis presents the analysis of the Word2Box algorithm and provides a comprehensive explanation of the codebase, including some considerations on its effectiveness in capturing semantic relationships and its potential to enhance natural language processing tasks.

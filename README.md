# TruncatedSVDupdates
Projection techniques to update the truncated SVD of evolving matrices with applications


In this work we present a new algorithm to update the truncatedSVD of evolving matrices, i.e., matrices which are periodically augmented with a new set of rows (and/or columns). The proposed algorithm undertakes a projection viewpoint and builds a pair of subspaces which approximate the linear span of the sought singular vectors of the evolving matrix.

For a complete description of the algorithm, please see our paper:

```

@InProceedings{pmlr-v139-kalantzis21a,
  title = 	 {Projection techniques to update the truncated SVD of evolving matrices with applications},
  author =       {Kalantzis, Vasileios and Kollias, Georgios and Ubaru, Shashanka and Nikolakopoulos, Athanasios N. and Horesh, Lior and Clarkson, Kenneth},
  booktitle = 	 {Proceedings of the 38th International Conference on Machine Learning},
  pages = 	 {5236--5246},
  year = 	 {2021},
  editor = 	 {Meila, Marina and Zhang, Tong},
  volume = 	 {139},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {18--24 Jul},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v139/kalantzis21a/kalantzis21a.pdf},
  url = 	 {https://proceedings.mlr.press/v139/kalantzis21a.html},
  abstract = 	 {This submission considers the problem of updating the rank-$k$ truncated Singular Value Decomposition (SVD) of matrices subject to the addition of new rows and/or columns over time. Such matrix problems represent an important computational kernel in applications such as Latent Semantic Indexing and Recommender Systems. Nonetheless, the proposed framework is purely algebraic and targets general updating problems. The algorithm presented in this paper undertakes a projection viewpoint and focuses on building a pair of subspaces which approximate the linear span of the sought singular vectors of the updated matrix. We discuss and analyze two different choices to form the projection subspaces. Results on matrices from real applications suggest that the proposed algorithm can lead to higher accuracy, especially for the singular triplets associated with the largest modulus singular values. Several practical details and key differences with other approaches are also discussed.}
}

```

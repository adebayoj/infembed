# Influence Embeddings

We have now released two separate implementations of the method described in the paper. 

The original proposal in the paper, which is based on the arnoldi iteration has now been include in the CAPTUM project. See this link for the [commit](https://github.com/pytorch/captum/pull/1187) that added it to captum, and [here](https://github.com/pytorch/captum/blob/master/captum/influence/_core/arnoldi_influence_function.py) for the implementation. 

More recently, we have also developed a stand alone package: [InfEmbed](https://github.com/guidelabs/infembed). The package includes a faster implementation of the Arnoldi-based influence computation. In addition, we also include a KFAC-based approach and a gradient-based baseline that has been found to be effective. We encourage you to check out the package, and ask questions there.

Thanks!
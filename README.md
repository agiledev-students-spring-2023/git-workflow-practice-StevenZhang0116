# Git Practice

## Interesting Article

[The Forward-Forward Algorithm: Some Preliminary Investigations](https://www.cs.toronto.edu/~hinton/FFA13.pdf)

## My Understanding

Professor Geoffrey Hinton have published this article in NeurIPS 2022. The basic idea is to run the forward process respectively on one positive data and one self-generated negative data. The logic is quite similar to GAN (Generative Adversarial Networks). Also, this work is related to local learning, which updates the weights layer by layer which is beneficial for the final decisions (not waiting until the end). In some cases (probably small-scale), this process might be more efficient since people do not need to know the details of the entire network. The argument of goodness function is quite appealing and leaves much freedom for the following developments. Specifically, he used two examples of "the sum of the squared neural activities and the negative sum of the squared activities", which are biologically reasonable. 
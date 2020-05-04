# Intro

Code for our BMVC 2019 paper [Image Classification with Hierarchical Multigraph Networks](https://arxiv.org/abs/1907.09000).

The code to extract superpixels can be found [in my another repo](https://github.com/bknyaz/graph_attention_pool).

**Update:**

In the code the `dist` variable should have been squared to make it a Gaussian. All figures and results were generated without squaring it. I don't think it's very important in terms of results, but if you square it, `sigma` should be adjusted accordingly.

# Blog

[Blog post explaining the paper](https://towardsdatascience.com/can-we-do-better-than-convolutional-neural-networks-46ed90fed807)

# Reference

Please cite our paper if you use our code:

```
@inproceedings{knyazev2019image,
  author = {Boris Knyazev and Xiao Lin and Mohamed R. Amer and Graham W. Taylor},
  title = {Image Classification with Hierarchical Multigraph Networks},
  booktitle = {British Machine Vision Conference (BMVC)},
  year = 2019,
  pdf = {https://arxiv.org/abs/1907.09000}
}
```

# PMMM 

We provide code for the Paper:

**[Differentiable Meta Multigraph Search with Partial Message Propagation on Heterogeneous Information Networks ][1]**\
Chao Li, Hao Xu, Kun He\
[AAAI 2023]

<img src='imgs/multigraph.png'/>



## Introduction 

Our main contributions are as follows:

1) To our knowledge, PMMM is the first NAS method to search multigraph as the architecture. We propose a new concept of meta multigraph to guide GNNs to propagate messages for NAS on HINs. 

2) We propose the first stable differentiable architecture search algorithm on HINs, called partial message search, which can consistently discover promising architectures that outperform hand-designed models. 

3) Thorough experiments are conducted to demonstrate the effectiveness, stability, and flexibility of our method. 



## Requisites

```
python=3.8
pytorch==1.6.0 with CUDA support (by default our model is trained on GPU)
numpy==1.19.1
scipy==1.5.2
pandas==1.1.1
scikit-learn==0.23.2
```



## Quick Start

For the node classification task, please see README under **node_classification**, and for the recommendation task, please see README under **recommendation**. 



## Citation

If you find this code and data useful, please consider citing the original work by authors:

```
@article{li2022differentiable,
  title={Differentiable Meta Multigraph Search with Partial Message Propagation on Heterogeneous Information Networks},
  author={Li, Chao and Xu, Hao and He, Kun},
  journal={arXiv preprint arXiv:2211.14752},
  year={2022}
}
```



[1]: https://arxiv.org/pdf/2211.14752.pdf

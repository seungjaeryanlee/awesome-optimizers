# awesome-optimizers

A curated list of optimizers for machine learning.

| Symbol | Meaning |
|-|-|
| ✔️ | Native support from PyTorch / TensorFlow |
| 🟡 | Non-native implementation |
| ❌ | No implementation found |

**TIP**: Click on ✔️ or 🟡 to view the implementation of that optimizer!

| Name | Date | Paper | PyTorch | TensorFlow |
|:----:|:----:|:------|:-------:|:----------:|
| SGD | | | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.SGD) | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/SGD) |
| RPROP | 1992 | [RPROP - A Fast Adaptive Learning Algorithm](https://www.semanticscholar.org/paper/RPROP-A-Fast-Adaptive-Learning-Algorithm-Riedmiller-Braun/02597de11d6b808ed0a4019f411f9ac7a9d426cb) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.Rprop) | ❌ |
| ASGD | 1992 | [Acceleration of stochastic approximation by averaging](https://dl.acm.org/doi/10.1137/0330046) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.ASGD) | ❌ |
| Adagrad | 2011 | [Adaptive Subgradient Methods for Online Learning and Stochastic Optimization](https://jmlr.csail.mit.edu/papers/v12/duchi11a.html) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.Adagrad) | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adagrad) |
| Adadelta | 2012 | [ADADELTA: An Adaptive Learning Rate Method](https://arxiv.org/abs/1212.5701) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.Adadelta) | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adadelta) |
| RMSprop | 2012 | [Neural Networks for Machine Learning Lecture 6a: Overview of mini-batch gradient descent](https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.RMSprop) | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/RMSprop) |
| Adam | 2014 | [Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adam) |
| Adamax | 2014 | [Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.Adamax) | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adamax) |
| Nadam | 2015 | [Incorporating Nesterov Momentum into Adam](http://cs229.stanford.edu/proj2015/054_report.pdf) | ❌ | [✔️](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Nadam) |
| AdamW | 2017 | [Decoupled Weight Decay Regularization](https://arxiv.org/abs/1711.05101) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.AdamW) | [🟡](https://www.tensorflow.org/addons/api_docs/python/tfa/optimizers/AdamW) |
| Yogi | 2018 | [Adaptive Methods for Nonconvex Optimization](https://papers.nips.cc/paper/8186-adaptive-methods-for-nonconvex-optimization) | [🟡](https://github.com/jettify/pytorch-optimizer#yogi) | [🟡](https://www.tensorflow.org/addons/api_docs/python/tfa/optimizers/Yogi) |
| AMSGrad | 2018 | [On the Convergence of Adam and Beyond](https://arxiv.org/abs/1904.09237) | [✔️](https://pytorch.org/docs/stable/optim.html#torch.optim.Adam) | ❌ |
| AdaBound | 2019 | [Adaptive Gradient Methods with Dynamic Bound of Learning Rate](https://arxiv.org/abs/1902.09843) | [🟡](https://github.com/Luolc/AdaBound) | ❌ |
| AMSBound | 2019 | [Adaptive Gradient Methods with Dynamic Bound of Learning Rate](https://arxiv.org/abs/1902.09843) | [🟡](https://github.com/Luolc/AdaBound) | ❌ |
| LAMB | 2019 | [Large Batch Optimization for Deep Learning: Training BERT in 76 minutes](https://arxiv.org/abs/1904.00962) |  ❌ | [🟡](https://www.tensorflow.org/addons/api_docs/python/tfa/optimizers/LAMB) |
| RAdam | 2019 | [On the Variance of the Adaptive Learning Rate and Beyond](https://arxiv.org/abs/1908.03265) | [🟡](https://github.com/LiyuanLucasLiu/RAdam) | [🟡](https://www.tensorflow.org/addons/api_docs/python/tfa/optimizers/RectifiedAdam) |
| SGDP | 2020 | [Slowing Down the Weight Norm Increase in Momentum-based Optimizers](https://arxiv.org/abs/2006.08217) | [🟡](https://github.com/clovaai/adamp) | ❌ |
| AdamP | 2020 | [Slowing Down the Weight Norm Increase in Momentum-based Optimizers](https://arxiv.org/abs/2006.08217) | [🟡](https://github.com/clovaai/adamp) | ❌ |
| Madam | 2020 | [Learning compositional functions via multiplicative weight updates](https://arxiv.org/abs/2006.14560) | [🟡](https://github.com/jxbz/madam) | ❌ |
| SuperAdam | 2021 | [Learning compositional functions via multiplicative weight updates](https://par.nsf.gov/servlets/purl/10316115) | [✔️](https://github.com/LIJUNYI95/SuperAdam) | ❌ |


## Other Resources

- [An overview of gradient descent optimization algorithms](https://ruder.io/optimizing-gradient-descent/)
- [torch-optimizer -- collection of optimizers for PyTorch compatible with optim module.](https://github.com/jettify/pytorch-optimizer)

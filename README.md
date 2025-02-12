# Differentially Private Deep Learning
This project focuses on applying Differential Privacy to deep learning.
The primary model used here is ResNet-20, although testing was also done on  WideResNet-16-4. 
For parallelization, Differentially Private Distributed Data Parallel (DPDDP) is used. We have also implemented the Differentially Private Importance Sampling algorithm from the [DPIS paper by Wei, et al.](https://arxiv.org/abs/2210.09634)

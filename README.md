# Wasserstein Exponential Kernels
Peer-reviewed version:
[H. De Plaen, M. Fanuel and J. A. K. Suykens, "Wasserstein Exponential Kernels," 2020 International Joint Conference on Neural Networks (IJCNN), 2020, pp. 1-6, doi: 10.1109/IJCNN48605.2020.9207630.](https://ieeexplore.ieee.org/document/9207630)

arXiv version:
[Henri De Plaen, Michaël Fanuel and Johan A. K. Suykens. *Wasserstein Exponential Kernels*, arXiv:2002.01878, Feb 2020.](https://arxiv.org/abs/2002.01878)

**Abstract** In the context of kernel methods, the similarity between data points is encoded by the kernel function which is often defined thanks to the Euclidean distance, a common example being the squared exponential kernel. Recently, other distances relying on optimal transport theory - such as the Wasserstein distance between probability distributions - have shown their practical relevance for different machine learning techniques. In this paper, we study the use of exponential kernels defined thanks to the regularized Wasserstein distance and discuss their positive definiteness. More specifically, we define Wasserstein feature maps and illustrate their interest for supervised learning problems involving shapes and images. Empirically, Wasserstein squared exponential kernels are shown to yield smaller classification errors on small training sets of shapes, compared to analogous classifiers using Euclidean distances.

### MATLAB
Just add everything to the path. Then run `mnist.m`, `quickdraw.m` or `usps.m`. You may want to comment/uncomment the computation of the distance matrices to avoid running it again at every run. You may also want to play with the parameters e.g. to run it on CPU or GPU (faster, but requires CUDA) or change the gridsearch bounds and resolution for the hyper-parameters tuning.

*Due to its size, the `quickdraw.mat` data-file is currently not uploaded. Before we finish to update it, please send us an email if you want to get your hands on it.*

**Packages required**
* [LS-SVMlab](https://www.esat.kuleuven.be/sista/lssvmlab/);
* [Sinkhorn Scaling for Optimal Transport](http://marcocuturi.net/SI.html).

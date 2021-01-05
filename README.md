
# GNN-hardware-acceleration-paper-collect
This repo is to collect the state-of-the-art GNN hardware acceleration paper

## GNN generic framework
**PYG: Fast Graph Representation Learning with PyTorch Geometric** [[PDF](https://arxiv.org/abs/1903.02428)][[github](https://github.com/rusty1s/pytorch_geometric)]

**DGL: Deep Graph Library (DGL)**, [[github](https://github.com/dmlc/dgl)]

## GCN training acceleration
Zeng, Hanqing, and Viktor Prasanna. "**Graphact: Accelerating gcn training on cpu-fpga heterogeneous platforms.**" The 2020 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. 2020 [[PDF](https://dl.acm.org/doi/abs/10.1145/3373087.3375312?casa_token=8kcTIaTaLeEAAAAA:d4AqDlFmWVDwh4w2cfF_zXljwnWNEDNjdI4xRHscrYpde5MJR4uwmganQPqEq1kfDOpFGQb5BCaB)]

Zeng, Hanqing, et al. "**Accurate, efficient and scalable graph embedding.**" 2019 IEEE International Parallel and Distributed Processing Symposium (IPDPS). IEEE, 2019. [[PDF](https://arxiv.org/abs/1810.11899)]


## GCN inference acceleration
Bingyi Zhang, Hanqing Zeng and Viktor Prasanna, **Hardware Acceleration of Large Scale GCN Inference**, The 31st IEEE International Conference on
Application-specific Systems, Architectures and Processors. [[PDF](https://asap2020.cs.manchester.ac.uk/paper.php?id=38)]

Yan, Mingyu, et al. "**Hygcn: A gcn accelerator with hybrid architecture.**" 2020 IEEE International Symposium on High Performance Computer Architecture (HPCA). IEEE, 2020. [[PDF](https://ieeexplore.ieee.org/abstract/document/9065592?casa_token=xYoRGK3KOlQAAAAA:d1tb6NVpA-JwTY7phB2DrorXzrXvawnommhjvemkHn2GSJCCmtKwljB5lXDuDmVgUkgBaiLG)]

Hwang, Ranggi, et al. "**Centaur: A Chiplet-based, Hybrid Sparse-Dense Accelerator for Personalized Recommendations.**" arXiv preprint arXiv:2005.05968 (2020). [[PDF](https://scholar.google.com/scholar?cluster=5865569946714123973&hl=en&as_sdt=0,5#d=gs_cit&u=%2Fscholar%3Fq%3Dinfo%3AxS4aF8qwZlEJ%3Ascholar.google.com%2F%26output%3Dcite%26scirp%3D0%26scfhb%3D1%26hl%3Den)]

**AWB-GCN: A Graph Convolutional Network Accelerator with Runtime Workload Rebalancing**. [[PDF](https://arxiv.org/abs/1908.10834)]

Kiningham, Kevin, Philip Levis, and Christopher Ré. "**GReTA: Hardware Optimized Graph Processing for GNNs.**" (2020). [[PDF](https://pdfs.semanticscholar.org/3594/237164f2d4e01172216a59a3158ed27d8fe3.pdf)]


## GNN inference acceleration
Liang, Shengwen, et al. "**DeepBurning-GL: an automated framework for generating graph neural network accelerators.**" 2020 IEEE/ACM International Conference On Computer Aided Design (ICCAD). IEEE, 2020. [[PDF](https://ieeexplore.ieee.org/abstract/document/9256539)]

Auten, Adam, Matthew Tomei, and Rakesh Kumar. "**Hardware Acceleration of Graph Neural Networks.**" [[PDF](https://passat.crhc.illinois.edu/dac20.pdf)]

He, Lei. "**EnGN: A High-Throughput and Energy-Efficient Accelerator for Large Graph Neural Networks.**" arXiv preprint arXiv:1909.00155 (2019). [[PDF](https://arxiv.org/abs/1909.00155)]


## Tensor accelerator evaluated using GNN

Srivastava, Nitish, et al. "**Tensaurus: A Versatile Accelerator for Mixed Sparse-Dense Tensor Computations.**" 2020 IEEE International Symposium on High Performance Computer Architecture (HPCA). IEEE, 2020. [[PDF](https://ieeexplore.ieee.org/abstract/document/9065579?casa_token=qNrM5wiIDHkAAAAA:5AQlnXs55-B2dzJ61pXf4_82-hBXJ-3KgHqVXYGybGKKO1Ip6h1zaiLtImNk8iy13hE8pLF5)]

## GNN accelerationg using GPGPU (general purpose graphic processing unit)

Guyue Huang, Guohao Dai, Yu Wang, Huazhong Yang, **GE-SpMM: General-purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks**, International Conference for High Performance Computing, Networking, Storage, and Analysis (SC'20) [[PDF](https://arxiv.org/abs/2007.03179)]

C. Tian, L. Ma, Z. Yang and Y. Dai, "**PCGCN: Partition-Centric Processing for Accelerating Graph Convolutional Network,**" 2020 IEEE International Parallel and Distributed Processing Symposium (IPDPS), New Orleans, LA, USA, 2020, pp. 936-945, doi: 10.1109/IPDPS47924.2020.00100 [[PDF](https://ieeexplore.ieee.org/abstract/document/9139807)]

**GNNAdvisor: An Efficient Runtime System for GNN Acceleration on GPUs** [[PDF](https://arxiv.org/pdf/2006.06608.pdf)]

M. Yan et al., "**Characterizing and Understanding GCNs on GPU**," in IEEE Computer Architecture Letters, vol. 19, no. 1, pp. 22-25, 1 Jan.-June 2020, doi: 10.1109/LCA.2020.2970395. [[PDF](https://ieeexplore.ieee.org/abstract/document/8976117)]

**NeuGraph: Parallel Deep Neural Network Computation on Large Graphs**, [[PDF](https://www.usenix.org/system/files/atc19-ma_0.pdf)]

## Contact
hguyue1@gmail.com

## Bio
I am a PhD student at Department of Electrical and Computer Engineering, UC Santa Barbara, starting from 2020. I work with Prof. [Yufei Ding](https://sites.cs.ucsb.edu/~yufeiding/) and Prof. [Yuan Xie](https://www.ece.ucsb.edu/~yuanxie/). Previously I received my B.E. in 2020 from Department of Electronic Engineering, Tsinghua University. 

My research interest is compiler for domain-specific accelerators. I also work on end-to-end optimization of DL training, through joint efforts from GPU kernel, compiler, GPU architecture and network. Below are some topics I have been working on:
* Deep Learning compiler (e.g., TVM)
* GPU sparse math kernels
* Sparse neural network and pattern pruning
* End-to-end training optimization for GNN, Transformer, Recommender Model
* GPU sparse tensor core design

[[Google Scholar page]](https://scholar.google.com/citations?user=_phoJY8AAAAJ&hl=en)

## Publications

[[SC'22][Transformer]](https://arxiv.org/abs/2110.05722) Xiaohui Wang, Yang Wei, Ying Xiong, **Guyue Huang**, Xian Qian, Yufei Ding, Mingxuan Wang, Lei Li. LightSeq2: Accelerated Training for Transformer-based Models on GPUs. *to appear, SC'22* 

[[DAC'22][Sparse NN]](https://dl.acm.org/doi/abs/10.1145/3489517.3530588) **Guyue Huang**, Haoran Li, Minghai Qin, Fei Sun, Yufei Ding and Yuan Xie. Shfl-BW: Accelerating Deep Neural Network Inference with Tensor-Core Aware Weight Pruning. DAC'22 [[preprint]](https://arxiv.org/abs/2203.05016)[[code]](https://github.com/hgyhungry/ShflBW_Sparse_NN)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L1)

[[DAC'22][GPU Sparse Kernel]](https://dl.acm.org/doi/10.1145/3489517.3530508) Guohao Dai, **Guyue Huang**, Shang Yang, Zhongming Yu, Hengrui Zhang, Yufei Ding, Yuan Xie, Huazhong Yang, Yu Wang. Heuristic Adaptability to Input Dynamics for SpMM on GPUs. Dac'22 (**Best Paper Nominee**) [[preprint]](https://arxiv.org/pdf/2202.08556.pdf)[[code]](https://github.com/hgyhungry/dgSPARSE-Library/tree/main/example)[bibtex]

[[MLSys'22][GNN System]](https://proceedings.mlsys.org/paper/2022/hash/9a1158154dfa42caddbd0694a4e9bdc8-Abstract.html) Hengrui Zhang, Zhongming Yu, Guohao Dai, **Guyue Huang**, Yufei Ding, Yuan Xie, Yu Wang. Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective.[[preprint]](https://arxiv.org/abs/2110.09524)[[code]](https://github.com/dgSPARSE/dgNN)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L9)

[[ICCD'21][GPU Sparse Kernel]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9643711) Zhongming Yu, Guohao Dai, **Guyue Huang**, Yu Wang and Huazhong Yang. Exploiting Online Locality and Reduction Parallelism for Sampled Dense Matrix Multiplication on GPUs. The 39th IEEE International Conference on Computer Design (ICCD), 2021. [[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L18)

[[ACM-SRC'21][GPU Sparse Kernel]](https://arxiv.org/abs/2106.16064) **Guyue Huang**, Guohao Dai, Yu Wang, Yufei Ding and Yuan Xie. Efficient Sparse Matrix Kernels based on Adaptive Workload-Balancing and Parallel-Reduction. 2021. ACM Student Research Competition (SRC), Graduate 3rd Place (https://src.acm.org)

[[TODAES'21][ML EDA]](https://dl.acm.org/doi/abs/10.1145/3451179) **Guyue Huang\***, Jingbo Hu\*, Yifan He\*, Jialong Liu\*, Mingyuan Ma\*, Chaoyang Shen\*, Juejian Wu\*, Yuanfan Xu\*, Hengrui Zhang\*, Kai Zhong\*, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, and Yu Wang,  Machine Learning for Electronic Design Automation: A Survey. [[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L27)

[[SC'20][GPU Sparse Kernel]](https://ieeexplore.ieee.org/document/9355302) **Guyue Huang**, Guohao Dai, Yu Wang and Huazhong Yang. GE-SpMM: General-purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks. The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2020. [[preprint]](https://arxiv.org/abs/2007.03179)[[code]](https://github.com/hgyhungry/ge-spmm)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L38)

## Work in Progress

[DL Compiler] Enabling Data Movement and Computation Pipelining in Deep Learning Compiler. [[preprint]](https://arxiv.org/abs/2210.16691)

## Awards
- DAC'22 best paper nomination
- Graduate 3rd Place, ACM Student Research Competition (2020) [[webpage]](https://src.acm.org/)

## Services
- MLSys'23 External Review Committee (ERC)

## Talks
- Talk at [[GTC 2022 Spring]](https://www.nvidia.com/gtc/?ncid=pa-srch-goog-950149): [dgSparseLib: New Algorithm and Adaptive Tuning for Sparse-dense Matrix Multiplication](https://events.rainfocus.com/widget/nvidia/gtcspring2022/sessioncatalog/session/1634865676629001SK4D)
- Talk at UCSB ECE graduate student lightning talk, about GPU sparse kernels

## Open-source
### ShflBW
ShflBW is a sparse NN kernel library, and also a pattern pruning method. Code released at [this repo](https://github.com/hgyhungry/ShflBW_Sparse_NN). Paper at [this link](https://arxiv.org/abs/2203.05016).

### dgSPARSE
The dgSPARSE project contains high-performance GPU kernels for sparse matrix primitives. We provide an interface to easily replace cuSPARSE in your existing applications. It contains
- GNN computational graph optimization [code](https://github.com/dgSPARSE/dgNN)  [paper](http://arxiv.org/abs/2110.09524)
- GPU SDDMM [code](https://github.com/dgSPARSE/dgSPARSE-Library/tree/main/src/sddmm) [paper](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/publications/2021/ICCD21_None.pdf)
- GPU SpMM [code](https://github.com/hgyhungry/dgSPARSE-Library/tree/main/example) [paper](https://arxiv.org/abs/2106.16064)

## HR reference keywords
* Computer Architecture - GPU arch - sparse computing / tensor-core 
* Machine learning - ML compiler - TVM 
* Machine learning - ML system - GNN / Recommendation-model / Transformer
* Parallel programming - GPU acceleration - sparse matrix kernels

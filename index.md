## Contact
hguyue1@gmail.com

## Bio
I am a PhD student at Department of Electrical and Computer Engineering, UC Santa Barbara, starting from 2020. I work with Prof. [Yufei Ding](https://sites.cs.ucsb.edu/~yufeiding/) and Prof. [Yuan Xie](https://www.ece.ucsb.edu/~yuanxie/). My research interest is computer architecture. 

Previously, I did an internship at Alibaba (Aug 2020-Sept 2021), focusing on GPU software. I received my B.E. from Department of Electronic Engineering, Tsinghua University. 


## Publications

[[DAC'22][Sparse NN]](https://arxiv.org/abs/2203.05016) **Guyue Huang**, Haoran Li, Minghai Qin, Fei Sun, Yufei Ding and Yuan Xie. Shfl-BW: Accelerating Deep Neural Network Inference with Tensor-Core Aware Weight Pruning. *to appear, DAC'22* [[code]](https://github.com/hgyhungry/ShflBW_Sparse_NN)

[[DAC'22][GPU Sparse Kernel]](https://arxiv.org/pdf/2202.08556.pdf) Guohao Dai, **Guyue Huang**, Shang Yang, Zhongming Yu, Hengrui Zhang, Yufei Ding, Yuan Xie, Huazhong Yang, Yu Wang. Heuristic Adaptability to Input Dynamics for SpMM on GPUs. *to appear, DAC'22*

[[MLSys'22][GNN System]](https://arxiv.org/abs/2110.09524) Hengrui Zhang, Zhongming Yu, Guohao Dai, **Guyue Huang**, Yufei Ding, Yuan Xie, Yu Wang. Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective.

[[ICCD'21][GPU Sparse Kernel]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9643711) Zhongming Yu, Guohao Dai, **Guyue Huang**, Yu Wang and Huazhong Yang. Exploiting Online Locality and Reduction Parallelism for Sampled Dense Matrix Multiplication on GPUs. The 39th IEEE International Conference on Computer Design (ICCD), 2021. 

[[ACM-SRC'21][GPU Sparse Kernel]](https://arxiv.org/abs/2106.16064)**Guyue Huang**, Guohao Dai, Yu Wang, Yufei Ding and Yuan Xie. Efficient Sparse Matrix Kernels based on Adaptive Workload-Balancing and Parallel-Reduction. 2021. ACM Student Research Competition (SRC), Graduate 3rd Place (https://src.acm.org)

[[TODAES'21][ML EDA]](https://dl.acm.org/doi/abs/10.1145/3451179) **Guyue Huang\***, Jingbo Hu\*, Yifan He\*, Jialong Liu\*, Mingyuan Ma\*, Chaoyang Shen\*, Juejian Wu\*, Yuanfan Xu\*, Hengrui Zhang\*, Kai Zhong\*, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, and Yu Wang,  Machine Learning for Electronic Design Automation: A Survey.

[[SC'20][GPU Sparse Kernel]](https://ieeexplore.ieee.org/document/9355302) **Guyue Huang**, Guohao Dai, Yu Wang and Huazhong Yang. GE-SpMM: General-purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks. The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2020. [[code]](https://github.com/hgyhungry/ge-spmm)

## Open-source
### ShflBW
ShflBW is a sparse NN kernel library, and also a pattern pruning method. Code released at [this repo](https://github.com/hgyhungry/ShflBW_Sparse_NN). Paper at [this link](https://arxiv.org/abs/2203.05016).

### dgSPARSE
The dgSPARSE project contains high-performance GPU kernels for sparse matrix primitives. We provide an interface to easily replace cuSPARSE in your existing applications. It contains
- GNN computational graph optimization [code](https://github.com/dgSPARSE/dgNN)  [paper](http://arxiv.org/abs/2110.09524)
- GPU SDDMM [code](https://github.com/dgSPARSE/dgSPARSE-Library/tree/main/src/sddmm) [paper](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/publications/2021/ICCD21_None.pdf)
- GPU SpMM [code](https://github.com/hgyhungry/dgSPARSE-Library/tree/main/example) [paper](https://arxiv.org/abs/2106.16064)

## Awards
- Graduate 3rd Place, ACM Student Research Competition (2020)

## News
- Talk at [GTC](https://www.nvidia.com/gtc/?ncid=pa-srch-goog-950149) Mar.24, 11AM (PDT), about fast GPU SpMM 
- Talk at ECE graduate student association lightning talk event, about GPU sparse kernels

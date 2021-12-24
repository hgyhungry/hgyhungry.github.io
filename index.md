## Contact
hguyue1@gmail.com

## Bio
I am a PhD student at Department of Electrical and Computer Engineering, UC Santa Barbara, starting from 2020. My advisors are Prof. [Yufei Ding](https://sites.cs.ucsb.edu/~yufeiding/) and Prof. Yuan Xie. My research interest is computer architecture. 

Previously, I did an internship at Alibaba (Aug 2020-Sept 2021), focusing on GPU software. I received my B.E. from Department of Electronic Engineering, Tsinghua University. 

[Google Scholar Page](https://scholar.google.com/citations?user=_phoJY8AAAAJ&hl=en)

## Publications
GPU sparse kernels
- Zhongming Yu, Guohao Dai, **Guyue Huang**, Yu Wang and Huazhong Yang. Exploiting Online Locality and Reduction Parallelism for Sampled Dense Matrix Multiplication on GPUs. The 39th IEEE International Conference on Computer Design (ICCD), 2021. 
- **Guyue Huang**, Guohao Dai, Yu Wang, Yufei Ding and Yuan Xie. Efficient Sparse Matrix Kernels based on Adaptive Workload-Balancing and Parallel-Reduction. 2021. ACM Student Research Competition (SRC), 2021 [[webpage]](https://src.acm.org) [[link]](https://arxiv.org/abs/2106.16064)
- **Guyue Huang**, Guohao Dai, Yu Wang and Huazhong Yang. GE-SpMM: General-purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks. The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2020. [[link]](https://ieeexplore.ieee.org/document/9355302)

GNN acceleration
- Hengrui Zhang, Zhongming Yu, Guohao Dai, **Guyue Huang**, Yufei Ding, Yuan Xie, Yu Wang. Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective. 2021. *preprint*. https://arxiv.org/abs/2110.09524. [[link]](https://arxiv.org/abs/2110.09524)

Others
- **Guyue Huang\***, Jingbo Hu\*, Yifan He\*, Jialong Liu\*, Mingyuan Ma\*, Chaoyang Shen\*, Juejian Wu\*, Yuanfan Xu\*, Hengrui Zhang\*, Kai Zhong\*, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, and Yu Wang,  Machine Learning for Electronic Design Automation: A Survey, TODAES, 2021 [[link]](https://dl.acm.org/doi/abs/10.1145/3451179)
- Qin Li, Huifeng Zhu, **Guyue Huang**, Zijie Yu, Fei Qiao, Qi Wei, Xinjun Liu, Huazhong Yang. Low-power in-pixel buffer circuit for smart image sensor. Sensor Review, 2020

## Project
dgSPARSE
The dgSPARSE project contains high-performance GPU kernels for sparse matrix primitives. We provide an interface to easily replace cuSPARSE in your existing applications. It contains
- GNN computational graph optimization [code](https://github.com/dgSPARSE/dgNN)  [paper](http://arxiv.org/abs/2110.09524)
- GPU SDDMM [code](https://github.com/dgSPARSE/dgSPARSE-Library/tree/main/src/sddmm) [paper](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/publications/2021/ICCD21_None.pdf)
- GPU SpMM [code](https://github.com/hgyhungry/dgSPARSE-Library/tree/main/example) [paper](https://arxiv.org/abs/2106.16064)

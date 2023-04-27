## Contact
hguyue1@gmail.com

## Bio
I am a PhD candidate at Department of Electrical and Computer Engineering, UC Santa Barbara, starting from 2020. I work with Prof. [Yufei Ding](https://sites.cs.ucsb.edu/~yufeiding/) and Prof. [Yuan Xie](https://www.ece.ucsb.edu/~yuanxie/). Previously I received my B.E. in 2020 from Department of Electronic Engineering, Tsinghua University. 

Below are some topics I have been working on:
* Deep Learning compiler (e.g., TVM)
* GPU sparse math kernels
* Sparse neural network and pattern pruning
* End-to-end training optimization for GNN, Transformer, Recommender Model
* GPU sparse tensor core design

[[Google Scholar page]](https://scholar.google.com/citations?user=_phoJY8AAAAJ&hl=en)

## Publications

[Mlsys'23] **Guyue Huang**, Yang Bai, Liu Liu, Yuke Wang, Bei Yu, Yufei Ding, Yuan Xie. ALCOP: Automatic Load-Compute Pipelining in Deep Learning Compiler for AI-GPUs. *To appear in Machine Learning and Systems, 2023*. [[preprint]](https://arxiv.org/abs/2210.16691)[[code]](https://github.com/hgyhungry/alcop-artifact)

[[SC'22]](https://arxiv.org/abs/2110.05722) Xiaohui Wang, Yang Wei, Ying Xiong, **Guyue Huang**, Xian Qian, Yufei Ding, Mingxuan Wang, Lei Li. LightSeq2: Accelerated Training for Transformer-based Models on GPUs. SC'22.

[[DAC'22]](https://dl.acm.org/doi/abs/10.1145/3489517.3530588) **Guyue Huang**, Haoran Li, Minghai Qin, Fei Sun, Yufei Ding and Yuan Xie. Shfl-BW: Accelerating Deep Neural Network Inference with Tensor-Core Aware Weight Pruning. DAC'22 [[preprint]](https://arxiv.org/abs/2203.05016)[[code]](https://github.com/hgyhungry/ShflBW_Sparse_NN)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L1)

[[DAC'22]](https://dl.acm.org/doi/10.1145/3489517.3530508) Guohao Dai, **Guyue Huang**, Shang Yang, Zhongming Yu, Hengrui Zhang, Yufei Ding, Yuan Xie, Huazhong Yang, Yu Wang. Heuristic Adaptability to Input Dynamics for SpMM on GPUs. Dac'22 (**Best Paper Nominee**) [[preprint]](https://arxiv.org/pdf/2202.08556.pdf)[[code]](https://github.com/hgyhungry/dgSPARSE-Library/tree/main/example)[bibtex]

[[MLSys'22]](https://proceedings.mlsys.org/paper/2022/hash/9a1158154dfa42caddbd0694a4e9bdc8-Abstract.html) Hengrui Zhang, Zhongming Yu, Guohao Dai, **Guyue Huang**, Yufei Ding, Yuan Xie, Yu Wang. Understanding GNN Computational Graph: A Coordinated Computation, IO, and Memory Perspective.[[preprint]](https://arxiv.org/abs/2110.09524)[[code]](https://github.com/dgSPARSE/dgNN)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L9)

[[ICCD'21]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9643711) Zhongming Yu, Guohao Dai, **Guyue Huang**, Yu Wang and Huazhong Yang. Exploiting Online Locality and Reduction Parallelism for Sampled Dense Matrix Multiplication on GPUs. The 39th IEEE International Conference on Computer Design (ICCD), 2021. [[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L18)

[[ACM-SRC'21 Poster]](https://arxiv.org/abs/2106.16064) **Guyue Huang**, Guohao Dai, Yu Wang, Yufei Ding and Yuan Xie. Efficient Sparse Matrix Kernels based on Adaptive Workload-Balancing and Parallel-Reduction. 2021. ACM Student Research Competition (SRC), Graduate 3rd Place (https://src.acm.org)

[[TODAES'21]](https://dl.acm.org/doi/abs/10.1145/3451179) **Guyue Huang\***, Jingbo Hu\*, Yifan He\*, Jialong Liu\*, Mingyuan Ma\*, Chaoyang Shen\*, Juejian Wu\*, Yuanfan Xu\*, Hengrui Zhang\*, Kai Zhong\*, Xuefei Ning, Yuzhe Ma, Haoyu Yang, Bei Yu, Huazhong Yang, and Yu Wang,  Machine Learning for Electronic Design Automation: A Survey. [[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L27)

[[SC'20]](https://ieeexplore.ieee.org/document/9355302) **Guyue Huang**, Guohao Dai, Yu Wang and Huazhong Yang. GE-SpMM: General-purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks. The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2020. [[preprint]](https://arxiv.org/abs/2007.03179)[[code]](https://github.com/hgyhungry/ge-spmm)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L38)

## Research Experiences

One of my research interests is **GPU sparse matrix kernels**, mainly targetting graph neural network (GNN) acceleration. I develop techniques to improve the memory access efficiency and input pattern adaptability for CUDA-based sparse matrix kernels. I have worked on SpMM acceleration and published [<ins>GE-SpMM</ins>](https://ieeexplore.ieee.org/document/9355302) (first-author paper at SC'20) and [<ins>DA-SpMM</ins>](https://dl.acm.org/doi/10.1145/3489517.3530508) (collaboration with [Dr. Guohao](https://scholar.google.com/citations?user=gz3Tkl0AAAAJ&hl=en), DAC'22 best paper candidate). I have also worked on GNN computational graph level optimizations and published a paper at [<ins>MLSys'22</ins>](https://proceedings.mlsys.org/paper/2022/hash/9a1158154dfa42caddbd0694a4e9bdc8-Abstract.html) (collaboration with [Hengrui](https://github.com/HenryChang213) and [Zhongming](https://github.com/fishmingyu)). Our research outcomes have been used by popular GNN frameworks like PyG and CogDL.

In parallel to GNN acceleration, I also work on **sparse neural network acceleration** and have published [<ins>Shfl-BW</ins>](https://dl.acm.org/doi/abs/10.1145/3489517.3530588)(first-author paper at DAC'22), which proposed a software-algorithm co-design method that combined the efficiency of block-wise pruning and the flexibility of unstructured pruning.

I also do research about **deep learning compiler**. I am interested in how to integrate advanced hardware features and analytical performance models into DL compilers to close the gap between compiler generated and manually developed kernels on DL accelerators. I mainly work on the TVM stack. My recent work [<ins>ALCOP</ins>](https://arxiv.org/abs/2210.16691)(first-author paper at MLSys'23) studies how to realize load-compute pipelining via compiler automation.

My recent research interest is architecture support for sparse computing. I am happy to discuss related research ideas with potential collaborators (please feel free to email me at guyue@ucsb.edu).

## Awards
- MLSys'22 Student Travel Grant
- DAC'22 best paper nomination
- ACM Student Research Competition (2020) Graduate 3rd Place [[webpage]](https://src.acm.org/)

## Services
- ISCA'23 AE Reviewer
- MLSys'23 External Review Committee (ERC)

## Talks
- Talk at [[TVMCon 2023]](https://www.youtube.com/playlist?list=PL_4zDggB-DBp81G1tAME9r0_P5IY9D700): [Enabling Data Movement and Computation Pipelining in Deep Learning Compiler](https://youtu.be/BC59piQj1qA)
- Talk at [[GTC 2022 Spring]](https://www.nvidia.com/gtc/?ncid=pa-srch-goog-950149): [dgSparseLib: New Algorithm and Adaptive Tuning for Sparse-dense Matrix Multiplication](https://events.rainfocus.com/widget/nvidia/gtcspring2022/sessioncatalog/session/1634865676629001SK4D)

## Open-source

### ALCOP
ALCOP is short for Automatic Load-COmpute Pipelining. This project presents a compiler pass based on TVM that pipelines the data movement and computation in GPU kernels. Code released at [this repo](https://github.com/hgyhungry/alcop-artifact). Paper at [this link](https://arxiv.org/abs/2210.16691).

### ShflBW
ShflBW is a sparse NN kernel library, and also a pattern pruning method. Code released at [this repo](https://github.com/hgyhungry/ShflBW_Sparse_NN). Paper at [this link](https://arxiv.org/abs/2203.05016).

### dgSPARSE
The dgSPARSE project contains high-performance GPU kernels for sparse matrix primitives. We provide an interface to easily replace cuSPARSE in your existing applications. It contains
- GNN computational graph optimization [code](https://github.com/dgSPARSE/dgNN)  [paper](http://arxiv.org/abs/2110.09524)
- GPU SDDMM [code](https://github.com/dgSPARSE/dgSPARSE-Library/tree/main/src/sddmm) [paper](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/publications/2021/ICCD21_None.pdf)
- GPU SpMM [code](https://github.com/hgyhungry/dgSPARSE-Library/tree/main/example) [paper](https://arxiv.org/abs/2106.16064)

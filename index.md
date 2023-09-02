## Contact
hguyue1@gmail.com

## Bio
I am a PhD candidate at Department of Electrical and Computer Engineering, UC Santa Barbara, starting from 2020. I work with Prof. [Yufei Ding](https://sites.cs.ucsb.edu/~yufeiding/) and Prof. [Yuan Xie](https://www.ece.ucsb.edu/~yuanxie/). Previously I received my B.E. in 2020 from Department of Electronic Engineering, Tsinghua University. 

My PhD research is focused on supporting sparsity in AI/DL on GPU. I am also interested in DL system and DL compiler.

[[Google Scholar page]](https://scholar.google.com/citations?user=_phoJY8AAAAJ&hl=en)

## Selected Publications
[MICRO'23] **Guyue Huang**, Zhengyang Wang, Po-An Tsai, Chen Zhang, Yufei Ding, Yuan Xie. RM-STC: Row-Merge Dataflow Inspired GPU Sparse Tensor Core for Energy-Efficient Sparse Acceleration. *To appear in 56th IEEE/ACM International Symposium on
Microarchitecture (MICRO-56), 2023*.

[[MLsys'23]](https://proceedings.mlsys.org/paper_files/paper/2023/hash/12a304a31e42dfefa21c82431e849124-Abstract-mlsys2023.html) **Guyue Huang**, Yang Bai, Liu Liu, Yuke Wang, Bei Yu, Yufei Ding, Yuan Xie. ALCOP: Automatic Load-Compute Pipelining in Deep Learning Compiler for AI-GPUs. Machine Learning and Systems, 2023. [[preprint]](https://arxiv.org/abs/2210.16691)[[code]](https://github.com/hgyhungry/alcop-artifact)

[[DAC'22]](https://dl.acm.org/doi/abs/10.1145/3489517.3530588) **Guyue Huang**, Haoran Li, Minghai Qin, Fei Sun, Yufei Ding and Yuan Xie. Shfl-BW: Accelerating Deep Neural Network Inference with Tensor-Core Aware Weight Pruning. DAC'22 [[preprint]](https://arxiv.org/abs/2203.05016)[[code]](https://github.com/hgyhungry/ShflBW_Sparse_NN)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L1)

[[ACM-SRC'21 Poster]](https://arxiv.org/abs/2106.16064) **Guyue Huang**, Guohao Dai, Yu Wang, Yufei Ding and Yuan Xie. Efficient Sparse Matrix Kernels based on Adaptive Workload-Balancing and Parallel-Reduction. 2021. ACM Student Research Competition (SRC), Graduate 3rd Place (https://src.acm.org)

[[SC'20]](https://ieeexplore.ieee.org/document/9355302) **Guyue Huang**, Guohao Dai, Yu Wang and Huazhong Yang. GE-SpMM: General-purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks. The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2020. [[preprint]](https://arxiv.org/abs/2007.03179)[[code]](https://github.com/hgyhungry/ge-spmm)[[bibtex]](https://github.com/hgyhungry/hgyhungry.github.io/blob/e132384030cb8a273b5c35e02d84582f04294ffc/paperbib#L38)

## Research Experiences

My PhD research is about supporting sparsity in AI/DL on GPU. Sparisty is a fascinating feature in modern deep learning that is both highly potential and extremely difficult for hardware to tackle. I investigate software and architecture methods to empower many forms of sparsity including weight sparsity, activation sparsity, graphs, embedding layers, and MoE. Refer to RM-STC (to appear, MICRO 2023), [<ins>Shfl-BW</ins>](https://dl.acm.org/doi/abs/10.1145/3489517.3530588) (DAC'22), [<ins>DA-SpMM</ins>](https://dl.acm.org/doi/10.1145/3489517.3530508) (DAC'22) and [<ins>GE-SpMM</ins>](https://ieeexplore.ieee.org/document/9355302) (SC'20).

I also do research about **deep learning compiler**. I am interested in how to integrate advanced hardware features and analytical performance models into DL compilers to close the gap between compiler generated and manually developed kernels on DL accelerators. I mainly work on the TVM stack. My recent work [<ins>ALCOP</ins>](https://arxiv.org/abs/2210.16691)(MLSys'23) studies how to realize load-compute pipelining via compiler automation.

## Awards
- MLSys'23 Student Travel Grant
- MLSys'22 Student Travel Grant
- DAC'22 best paper nomination
- ACM Student Research Competition (2020) Graduate 3rd Place [[webpage]](https://src.acm.org/)

## Services
- TODAES Paper Reviewer
- ISCA'23 Artifact Evaluation Reviewer
- DAC'23 Reviewer
- MLSys'23 Extended Review Committee

## Internship
- 2023 summer. NVIDIA. Deep Learning Architect Intern.
- 2022 summer. NVIDIA. Deep Learning Architect Intern.

## Talks
- (2023/3) Talk at Google, ML+Compiler Reading Group: Enabling Data Movement and Computation Pipelining in Deep Learning Compiler. 
- (2023/3) Talk at [[TVMCon 2023]](https://www.youtube.com/playlist?list=PL_4zDggB-DBp81G1tAME9r0_P5IY9D700): [Enabling Data Movement and Computation Pipelining in Deep Learning Compiler](https://youtu.be/BC59piQj1qA)
- (2022/11) Talk at AWS, Scale Team: Enabling Data Movement and Computation Pipelining in Deep Learning Compiler.
- (2022/3) Talk at [[GTC 2022 Spring]](https://www.nvidia.com/gtc/?ncid=pa-srch-goog-950149): [dgSparseLib: New Algorithm and Adaptive Tuning for Sparse-dense Matrix Multiplication](https://events.rainfocus.com/widget/nvidia/gtcspring2022/sessioncatalog/session/1634865676629001SK4D)

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

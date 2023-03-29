# awesome-deep-gnn
![contributing-image](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

Papers about **developing deep Graph Neural Networks (GNNs)**. Investigations about **over-smoothing** and **over-squashing** problem in GNNs are also included here.

**Please feel free to submit a pull request if you want to add good papers.**

<!-- ## Literature [sorted in reverse chronological order]-->


Most Influential Papers 
----
Selected by [CogDL](https://github.com/THUDM/cogdl/blob/master/gnn_papers.md#oversmoothing-and-deep-gnns)

1. [ICML 2018] **Representation Learning on Graphs with Jumping Knowledge Networks** [[Paper]](https://arxiv.org/abs/1806.03536)
2. [AAAI 2018] **Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning** [[Paper]](https://arxiv.org/abs/1801.07606)
3. [ICLR 2019] **Predict then Propagate: Graph Neural Networks meet Personalized PageRank** [[Paper]](https://arxiv.org/abs/1810.05997)[[Code]](https://github.com/klicperajo/ppnp)
4. [ICCV 2019] **DeepGCNs: Can GCNs Go as Deep as CNNs?** [[Paper]](https://arxiv.org/abs/1904.03751)[[Code(Pytorch)]](https://github.com/lightaime/deep_gcns_torch)[[Code(TensorFlow)]](https://github.com/lightaime/deep_gcns)
5. [NeurIPS 2019] **Layer-Dependent Importance Sampling for Training Deep and Large Graph Convolutional Networks.** [[Paper]](https://arxiv.org/abs/1911.07323)[[Code]](https://github.com/UCLA-DM/LADIES)
6. [arXiv 2020] **DeeperGCN: All You Need to Train Deeper GCNs** [[Paper]](https://arxiv.org/abs/2006.07739)[[Code]](https://github.com/lightaime/deep_gcns_torch)
7. [ICLR 2020] **PairNorm: Tackling Oversmoothing in GNNs** [[Paper]](https://openreview.net/forum?id=rkecl1rtwB)[[Code]](https://github.com/LingxiaoShawn/PairNorm)
8. [ICLR 2020] **DropEdge: Towards Deep Graph Convolutional Networks on Node Classification** [[Paper]](https://openreview.net/forum?id=Hkx1qkrKPr)[[Code]](https://github.com/DropEdge/DropEdge)
9. [ICML 2020] **Simple and Deep Graph Convolutional Networks** [[Paper]](https://arxiv.org/abs/2007.02133)[[Code]](https://github.com/chennnM/GCNII)
10. [KDD 2020] **Towards Deeper Graph Neural Networks** [[Paper]](https://arxiv.org/abs/2007.09296)[[Code]](https://github.com/mengliu1998/DeeperGNN)

2022
----

* [NeurIPS 2022] **Not too little, not too much: a theoretical analysis of graph (over)smoothing** [[Paper]](https://arxiv.org/abs/2205.12156)[[Code]](https://github.com/twitter-research/neural-sheaf-diffusion)
* [NeurIPS 2022] **Neural Sheaf Diffusion: A Topological Perspective on Heterophily and Oversmoothing in GNNs** [[Paper]](https://arxiv.org/abs/2202.04579)[[Code]](https://github.com/twitter-research/neural-sheaf-diffusion)
* [ICML 2022] **Graph-Coupled Oscillator Networks** [[Paper]](https://arxiv.org/abs/2202.02296)[[Code]](https://github.com/tk-rusch/graphcon)
* [KDD 2022] **Feature Overcorrelation in Deep Graph Neural Networks: A New Perspective** [[Paper]](https://arxiv.org/abs/2206.07743) [[code]](https://github.com/ChandlerBang/DeCorr)
* [KDD 2022] **Model Degradation Hinders Deep Graph Neural Networks** [[Paper]](https://arxiv.org/abs/2206.04361)
* [ICDM 2022] **Two Sides of the Same Coin: Heterophily and Oversmoothing in Graph Convolutional Neural Networks** [[Paper]](https://arxiv.org/abs/2102.06462)[[Code]](https://github.com/yujun-yan/heterophily_and_oversmoothing)
* [ICLR 2022] **Understanding over-squashing and bottlenecks on graphs via curvature** [[Paper]](https://openreview.net/forum?id=7UmjRGzp-A)[[Code]](https://github.com/jctops/understanding-oversquashing)
* [ICLR 2022] **Towards Deepening Graph Neural Networks: A GNTK-based Optimization Perspective** [[Paper]](https://openreview.net/forum?id=tT9t_ZctZRL)
* [ICLR 2022] **Simple GNN Regularisation for 3D Molecular Property Prediction & Beyond** [[Paper]](https://arxiv.org/abs/2106.07971)
* [ICLR 2022] **Revisiting Over-smoothing in BERT from the Perspective of Graph** [[Paper]](https://openreview.net/forum?id=dUV91uaXm3)
* [AAAI 2022] **Orthogonal Graph Neural Networks** [[Paper]](https://arxiv.org/abs/2109.11338)
* [TPAMI] **Bag of Tricks for Training Deeper Graph Neural Networks: A Comprehensive Benchmark Study**  [[Paper]](https://arxiv.org/abs/2108.10521)[[Code]](https://github.com/VITA-Group/Deep_GCN_Benchmarking)


2021
----

* [ICML 2021] **Lipschitz Normalization for Self-Attention Layers with Application to Graph Neural Networks** [[Paper]](https://arxiv.org/abs/2103.04886)
* [ICML 2021] **Improving Breadth-Wise Backpropagation in Graph Neural Networks Helps Learning Long-Range Dependencies** [[Paper]](http://proceedings.mlr.press/v139/lukovnikov21a/lukovnikov21a.pdf)
* [ICML 2021] **GRAND: Graph Neural Diffusion** [[Paper]](https://arxiv.org/abs/2106.10934)[[Code]](https://github.com/twitter-research/graph-neural-pde)
* [ICML 2021] **Graph Neural Networks Inspired by Classical Iterative Algorithms** [[Paper]](https://arxiv.org/abs/2103.06064)[[Code]](https://github.com/FFTYYY/TWIRLS)
* [ICML 2021] **Optimization of Graph Neural Networks: Implicit Acceleration by Skip Connections and More Depth** [[Paper]](https://arxiv.org/abs/2105.04550)
* [ICML 2021] **Training Graph Neural Networks with 1000 Layers** [[Paper]](https://arxiv.org/abs/2106.07476)[[Code]](https://github.com/lightaime/deep_gcns_torch)
* [ICML 2021] **Directional Graph Networks** [[Paper]](https://arxiv.org/abs/2010.02863)[[Code]](https://github.com/Saro00/DGN)
* [ICLR 2021] **AdaGCN: Adaboosting Graph Convolutional Networks into Deep Models** [[Paper]](https://arxiv.org/abs/1908.05081)[[Code]](https://github.com/datake/AdaGCN)
* [ICLR 2021] **On the Bottleneck of Graph Neural Networks and its Practical Implications** [[Paper]](https://openreview.net/forum?id=i80OPhOCVH2)[[Code]](https://github.com/tech-srl/bottleneck/)
* [ICLR 2021] **Adaptive Universal Generalized PageRank Graph Neural Network** [[Paper]](https://openreview.net/forum?id=n6jl7fLxrP)[[Code]](https://github.com/jianhao2016/GPRGNN)
* [ICLR 2021] **Simple Spectral Graph Convolution** [[Paper]](https://openreview.net/forum?id=CYO5T-YjWZV)
* [CIKM 2021] **Understanding and Resolving Performance Degradation in Graph Convolutional Networks** [[Paper]](https://arxiv.org/abs/2006.07107)[[Code]](https://github.com/miafei/NodeNorm)


2020
----

* [arXiv 2020] **Deep Graph Neural Networks with Shallow Subgraph Samplers** [[Paper]](https://arxiv.org/abs/2012.01380)
* [arXiv 2020] **Revisiting Graph Convolutional Network on Semi-Supervised Node Classification from an Optimization Perspective** [[Paper]](https://arxiv.org/abs/2009.11469)
* [arXiv 2020] **Tackling Over-Smoothing for General Graph Convolutional Networks** [[Paper]](https://arxiv.org/abs/2008.09864)
* [arXiv 2020] **DeeperGCN: All You Need to Train Deeper GCNs** [[Paper]](https://arxiv.org/abs/2006.07739)[[Code]](https://github.com/lightaime/deep_gcns_torch)
* [arXiv 2020] **Revisiting Over-smoothing in Deep GCNs** [[paper]](https://arxiv.org/abs/2003.13663)
<br/><br/>
* [NeurIPS 2020] **Graph Random Neural Networks for Semi-Supervised Learning on Graphs** [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/fb4c835feb0a65cc39739320d7a51c02-Abstract.html)[[Code]](https://github.com/THUDM/GRAND)
* [NeurIPS 2020] **Scattering GCN: Overcoming Oversmoothness in Graph Convolutional Networks** [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/a6b964c0bb675116a15ef1325b01ff45-Abstract.html)[[Code]](https://github.com/dms-net/scatteringGCN)
* [NeurIPS 2020] **Optimization and Generalization Analysis of Transduction through Gradient Boosting and Application to Multi-scale Graph Neural Networks** [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/dab49080d80c724aad5ebf158d63df41-Abstract.html)[[Code]](https://github.com/delta2323/GB-GNN)
* [NeurIPS 2020] **Towards Deeper Graph Neural Networks with Differentiable Group Normalization** [[Paper]](https://arxiv.org/abs/2006.06972)
* [ICML 2020 Workshop GRL+] **A Note on Over-Smoothing for Graph Neural Networks** [[Paper]](https://arxiv.org/abs/2006.13318)
* [ICML 2020] **Bayesian Graph Neural Networks with Adaptive Connection Sampling** [[Paper]](https://arxiv.org/abs/2006.04064)
* [ICML 2020] **Continuous Graph Neural Networks** [[Paper]](https://arxiv.org/abs/1912.00967)
* [ICML 2020] **Simple and Deep Graph Convolutional Networks** [[Paper]](https://arxiv.org/abs/2007.02133)[[Code]](https://github.com/chennnM/GCNII)
* [KDD 2020] **Towards Deeper Graph Neural Networks** [[Paper]](https://arxiv.org/abs/2007.09296)[[Code]](https://github.com/mengliu1998/DeeperGNN)
* [ICLR 2020] **Graph Neural Networks Exponentially Lose Expressive Power for Node Classification** [[Paper]](https://arxiv.org/abs/1905.10947)[[Code]](https://github.com/delta2323/gnn-asymptotics)
* [ICLR 2020] **DropEdge: Towards Deep Graph Convolutional Networks on Node Classification** [[Paper]](https://openreview.net/forum?id=Hkx1qkrKPr)[[Code]](https://github.com/DropEdge/DropEdge)
* [ICLR 2020] **PairNorm: Tackling Oversmoothing in GNNs** [[Paper]](https://openreview.net/forum?id=rkecl1rtwB)[[Code]](https://github.com/LingxiaoShawn/PairNorm)
* [ICLR 2020] **Measuring and Improving the Use of Graph Information in Graph Neural Networks** [[Paper]](https://openreview.net/forum?id=rkeIIkHKvS)[[Code]](https://github.com/yifan-h/CS-GNN)
* [AAAI 2020] **Measuring and Relieving the Over-smoothing Problem for Graph Neural Networks from the Topological View** [[Paper]](https://arxiv.org/abs/1909.03211)
* [CVPR 2020] **Geometrically Principled Connections in Graph Neural Networks** [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Gong_Geometrically_Principled_Connections_in_Graph_Neural_Networks_CVPR_2020_paper.html)

Before 2020
----

* [arXiv 2019] **Revisiting Graph Neural Networks: All We Have is Low-Pass Filters** [[Paper]](https://arxiv.org/abs/1905.09550)
<br/><br/>
* [NeurIPS 2019] **Break the Ceiling: Stronger Multi-scale Deep Graph Convolutional Networks** [[Paper]](https://arxiv.org/abs/1906.02174)
* [NeurIPS 2019] **Layer-Dependent Importance Sampling for Training Deep and Large Graph Convolutional Networks.** [[Paper]](https://arxiv.org/abs/1911.07323)[[Code]](https://github.com/UCLA-DM/LADIES)
* [ICLR 2019] **Predict then Propagate: Graph Neural Networks meet Personalized PageRank** [[Paper]](https://arxiv.org/abs/1810.05997)[[Code]](https://github.com/klicperajo/ppnp)
* [ICCV 2019] **DeepGCNs: Can GCNs Go as Deep as CNNs?** [[Paper]](https://arxiv.org/abs/1904.03751)[[Code(Pytorch)]](https://github.com/lightaime/deep_gcns_torch)[[Code(TensorFlow)]](https://github.com/lightaime/deep_gcns)
* [ICML 2018] **Representation Learning on Graphs with Jumping Knowledge Networks** [[Paper]](https://arxiv.org/abs/1806.03536)
* [AAAI 2018] **Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning** [[Paper]](https://arxiv.org/abs/1801.07606)









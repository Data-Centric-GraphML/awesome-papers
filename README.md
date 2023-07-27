# Awesome-Data-Centric-GraphML
A collection of papers and resources about Data-centric Graph Machine Learning (DC-GML)



## How To Enhance Graph Data Availability and Quality? --Graph Data Improvement
### Graph Structure Enhancement
#### Graph Structure Learning
- [KDD'2020-Pro-GNN] Graph structure learning for robust graph neural networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403049)
- [ICML'2019-LDS] Learning discrete structures for graph
neural networks. [[paper]](http://proceedings.mlr.press/v97/franceschi19a/franceschi19a.pdf)
- [WWW'2021-GEN] Graph structure estimation neural networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449952?casa_token=WBEXRhs6I_YAAAAA:cVk3EONP8EwXVzuUSZp8Qp-gZOLEVJYHDLV-hXTJ-gh5v-I_LuTYfvxKlk_Y5rOUfFKYZW9ty5xKg1w)
- [CVPR'2019-GLCN] Semi-supervised learning with graph learning convolutional networks. [[paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jiang_Semi-Supervised_Learning_With_Graph_Learning-Convolutional_Networks_CVPR_2019_paper.pdf)
- [NIPS'2020-IDGL] Iterative deep graph learning for graph neural networks: Better and robust node embeddings. [[paper]](https://proceedings.neurips.cc/paper/2020/file/e05c7ba4e087beea9410929698dc41a6-Paper.pdf)
#### Graph Sparsification
- [AIS'2016] Graph sparsification approaches for laplacian smoothing. [[paper]](http://proceedings.mlr.press/v51/sadhanala16.pdf)
- [SIGMOD'2011] Local graph sparsification for scalable clustering. [[paper]](https://dl.acm.org/doi/pdf/10.1145/1989323.1989399?casa_token=_CYKRbVjXTcAAAAA:WGIgqzcngwWBBkw9of3Wbjrc8JES8cAw39VQKKkTlVzB_MA_IQoCDyTd7rLe_1609i0wVXIPt8O3dpY)
- [SICOMP'2011] Spectral sparsification of graphs.[[paper]](https://arxiv.org/pdf/0808.4134)
- [NIPS'2019] On differentially private graph sparsification and applications. [[paper]](https://proceedings.neurips.cc/paper/2019/file/e44e875c12109e4fa3716c05008048b2-Paper.pdf)
- [ICDM'2022-GraphSparsify] A generic graph sparsification framework using deep reinforcement learning. [[paper]](https://ieeexplore.ieee.org/iel7/10027565/10027596/10027736.pdf?casa_token=ST116wBmpbMAAAAA:jfGOFwHoX4AsOiSUQYYNV6BUuC_mUKaPG5aKVTvSzK0PkJulHXAYk-Is9MzRSLISUhHZnQlIaEDN)
#### Graph Diffusion
- [ICLR'2019-PPNP/APPNP] Predict then propagate: graph neural networks meet personalized pagerank. [[paper]](https://arxiv.org/pdf/1810.05997)
- [NIPS'2019-GDC] Diffusion improves graph learning. [[paper]](https://proceedings.neurips.cc/paper/2019/file/23c894276a2c5a16470e6a31f4618d73-Paper.pdf)
- [ICLR'2021] Adaptive universal generalized pagerank graph neural network. [[paper]](https://arxiv.org/pdf/2006.07988)
- [NIPS'2021-ADC] Adaptive diffusion in graph neural networks. [[paper]](https://proceedings.neurips.cc/paper/2021/file/c42af2fa7356818e0389593714f59b52-Paper.pdf)
### Graph Feature Enhancement
#### Graph Feature Completion
- [NN'2020-GINN] Missing data imputation with adversarially-trained graph convolutional networks. [[paper]](https://www.sciencedirect.com/science/article/pii/S0893608020302185?casa_token=I7BtgyazKl8AAAAA:edsPKQbKSp1fbciuDc76aYnSPSS6T03ESUb_i2KDUJ6o2cA5LVCS-K8SfkhgWCqi5Bqog9hihvU)
- [FGCS'2021-GCN_MF] Graph convolutional networks for graphs containing missing features. [[paper]](https://www.sciencedirect.com/science/article/pii/S0167739X20330405)
- [TPAMI'2020-SAT] Learning on attribute-missing graphs. [[paper]](https://ieeexplore.ieee.org/iel7/34/4359286/09229522.pdf?casa_token=TsPVGT_mK-AAAAAA:XJ-eH3DCQ5OnkXvj5UhHBb8IC8O_I3WyworEudS9D2c-E7usbAovpaNswysThFSCPWWq94Az9EU-)
- [WWW'2021-HGNN-AC] Heterogeneous graph neural network via attribute completion. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449914?casa_token=N3XrnbFD-VsAAAAA:aJnfUQvXnC-7T2INzKCmo3kLYGa1qJ1Z_EgTPH5gSRblwPFvlUCxg1sXgmnOcBSRLR-VuE6_Cv-DLM8)
- [IEEETransCybern'2022-Amer] Amer: A new attribute-missing network embedding approach. [[paper]](https://ieeexplore.ieee.org/iel7/6221036/6352949/09765782.pdf?casa_token=TNBxp_Z_qf8AAAAA:VPKCn0964kuE4tJZPTvUG1xAP2MEy_QvA0ym6ry8Cvu28BuFqUkG2P9xYGmXDx13TUvC_6NBu5V1)
- [arxiv'2021-SAGA] Siamese attribute-missing graph auto-encoder. [[paper]](https://arxiv.org/pdf/2112.04842)
#### Graph Feature Denoising
- [SPM'2013] The emerging field of signal processing on graphs: Extending high-dimensional data analysis to networks and other irregular domains. [[paper]](https://ieeexplore.ieee.org/iel7/79/6494646/06494675.pdf?casa_token=mD3rZmt2imAAAAAA:dtVEN95FqjgPHlO9pQ_c-xTtDMPuknx3pdjPVIkffAMEkoCRW-26vAq8gbjlXCh1Q02tEUbPHg)
- [GlobalSIP'2014] Signal denoising on graphs via graph filtering. [[paper]](https://ieeexplore.ieee.org/iel7/7010655/7032060/07032244.pdf?casa_token=EyFQK1dNZTUAAAAA:wzIP7ZxTWQQHcy4pfRmk3_JrDv39r8VyIXueZ_Y25VVeXHixoOP0mIMckQAn2prDBZO6EnfpFM8P)
- [IET-SP'2018] Graph polynomial filter for signal denoising. [[paper]](https://scholar.google.com/scholar?output=instlink&q=info:N5LbqcYw_6AJ:scholar.google.com/&hl=zh-CN&as_sdt=0,5&scillfp=17975566870893489622&oi=lle)
- [AIS'2015] Trend filtering on graphs. [[paper]](http://proceedings.mlr.press/v38/wang15d.pdf)
- [ICASSP'2020] Graph auto-encoder for graph signal denoising. [[paper]](https://ieeexplore.ieee.org/iel7/9040208/9052899/09053623.pdf?casa_token=wp6nKhBq4eQAAAAA:VbeeBWniW1nbGLsSSTDaOlUt8Co50jVEejxpZQziCDzx8NnIJ_0ZPGVdJNi5GG9pRKAaA-rENrOL)
- [TSP'2021] Graph unrolling networks: Interpretable neural networks for graph signal denoising. [[paper]](https://ieeexplore.ieee.org/iel7/78/4359509/09453145.pdf?casa_token=WBFBG92sg-wAAAAA:CFc6t1fhHyEQleL3nCQiBE5XNjTGFqS80VXxkHSDPEPzS7OEed6ydOV7M0ZN-yKlrkljWt-sXKh7)
- [TSP'2022] Untrained graph neural networks for denoising. [[paper]](https://ieeexplore.ieee.org/iel7/78/4359509/09959969.pdf?casa_token=79riV29MxvkAAAAA:kEUgypSxBhsj1TqD-3vTPxUY1JoHN5E6vTh2uFkuJrSTiA7bGt6qIorsfuHB3kxczHZGkyH8E0Um)
- [WWW'2023-MAGNET] Robust graph representation learning for local corruption recovery. [[paper]](https://yuguangwang.github.io/papers/L_p_graph_regularizer_ICML%20TAG%202022.pdf)
### Graph Label Enhancement
#### Graph Pseudo-labeling
- [AAAI'2018] Deeper insights into graph convolutional networks for semi-supervised learning. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/11604/11463)
- [AAAI'2020] Multi-stage self-supervised learning for graph convolutional networks on graphs with few labeled nodes. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/6048/5904)
- [CIKM'2021-IFC-GCN] Rectifying pseudo labels: Iterative feature clustering for graph representation learning. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482469?casa_token=j-229ROWIHwAAAAA:ubON8KC_ifOtZWU2MqrFg3ZAiloxu2JGcOWWSdIZcKj-qlfgeRzL0xclkB8DF6lxs_Qcmj1lz9UFTOo)
- [arXiv'2019-DSGCN] Dynamic self-training framework for graph convolutional networks. [[paper]](https://openreview.net/pdf?id=SJgCEpVtvr)
- [WSDM'2022-RS-GNN] Towards robust graph neural networks for noisy graphs with sparse labels. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3488560.3498408)
- [DMKD'2023-InfoGNN] Informative pseudo-labeling for graph neural networks with few labels. [[paper]](https://link.springer.com/article/10.1007/s10618-022-00879-4)
#### Graph Label Denoising
- [WSDM'2023-CLNode] CLNode: Curriculum learning for node classification. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3539597.3570385?casa_token=cNDTalzkl6IAAAAA:0-d5yP4lt002LAiXl9dHRFQ7iARGawdtBSZ4rVR29UeBHabh8yC7YvjAJdAac3SKLutBKX_HrN1CNts)
- [arXiv'2019-D-GNN] Learning graph neural networks with noisy labels. [[paper]](https://arxiv.org/pdf/1905.01591)
- [CIKM'2021-IFC-GCN] Rectifying pseudo labels: Iterative feature clustering for graph representation learning. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3459637.3482469?casa_token=j-229ROWIHwAAAAA:ubON8KC_ifOtZWU2MqrFg3ZAiloxu2JGcOWWSdIZcKj-qlfgeRzL0xclkB8DF6lxs_Qcmj1lz9UFTOo)
- [KDD'2021-NRGNN] Nrgnn: Learning a label noise resistant graph neural network on sparsely and noisily labeled graphs. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467364)
- [WSDM'2023-RTGNN] Robust training of graph neural networks via noise governance. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3539597.3570369?casa_token=9LQOlvbtC2AAAAAA:qmY_CT3ipOgGls6v5El4psDQ8tCMZpZfkRiSfBVAI32kXMTNkH2p9ZTQYLC2yUVoOjZJDEB5g27sEDo)
#### Graph Class-imbalanced Sampling
- [WSDM'2021-GraphSMOTE] Graphsmote: Imbalanced node classification on graphs with graph neural networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3437963.3441720)
- [KDD'2021-ImGAGN] Imgagn: Imbalanced network embedding via generative adversarial graph networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467334?casa_token=4G06vl98C9IAAAAA:YgtmaAMJO5uyHdy3XRNwiw9MQ-SwbVMNSC0M1FkVpbiw0n1XGkGkICXjl3urOfXVUDjsbjiwFWYhxOk)
- [WWW'2021-PC-GNN] Pick and choose: a GNN-based imbalanced learning approach for fraud detection. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449989)
- [WWW'2021-GraphMixup] Mixup for node and graph classification. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449796)
- [ICLR'2021-GraphENS] GraphENS: Neighbor-aware ego network synthesis for class-imbalanced node classification. [[paper]](https://openreview.net/pdf?id=MXEl7i-iru)
- [arXiv'2023-GraphSR] GraphSR: A Data Augmentation Algorithm for Imbalanced Node Classification. [[paper]](https://arxiv.org/pdf/2302.12814)
- [NIPS'2021-ReNode] Topology-imbalance learning for semi-supervised node classification. [[paper]](https://proceedings.neurips.cc/paper/2021/file/fa7cdfad1a5aaf8370ebeda47a1ff1c3-Paper.pdf)
- [arXiv'2022-TopoImb] TopoImb: Toward topology-level imbalance in learning from graphs. [[paper]](https://arxiv.org/pdf/2212.08689)
- [IJCAI'2013-igBoost] Graph classification with imbalanced class distributions and noise. [[paper]](https://www.researchgate.net/profile/Shirui-Pan-3/publication/262204599_Graph_classification_with_imbalanced_class_distributions_and_noise/links/564bc59d08ae3374e5dddb5b/Graph-classification-with-imbalanced-class-distributions-and-noise.pdf)
- [CIKM'2022-G2GNN] Imbalanced graph classification via graph-of-graph neural networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557356?casa_token=gzP3pWpfsWMAAAAA:BPdp0A0Mh3tWlXo6i4Mvd5kfVo0geTqqfH_hOyCpAki9krAMdq6fZKCScHffiQdfq9mZSPYBRR85uL4)
### Graph Size Enhancement
#### Graph Size Reduction
- [ICML'2009-Herding] Herding dynamical weights to learn. [[paper]](https://dl.acm.org/doi/pdf/10.1145/1553374.1553517?casa_token=mSkkhW5jA84AAAAA:31mF183Hzi4X1un4BsuRLuaFVId7Febx4PXXQbbZ0uquebekHdDhncU3QhaH0zxb6ItnWYdWehkfhFM)
- [CVPR'2017-ICARL] ICARL: Incremental classifier and representation learning. [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Rebuffi_iCaRL_Incremental_Classifier_CVPR_2017_paper.pdf)
- [ICLR'2018-K-center] Active learning for convolutional neural networks: A core-set approach. [[paper]](https://arxiv.org/pdf/1708.00489.pdf)
- [ICAIS'2020-Coarsening] Graph coarsening with preserved spectral properties. [[paper]](http://proceedings.mlr.press/v108/jin20a/jin20a.pdf)
- [arXiv'2021] Graph domain adaptation: A generative view. [[paper]](https://arxiv.org/pdf/2106.07482)
- [ICLR'2021-GCond] Graph condensation for graph neural networks. [[paper]](https://arxiv.org/pdf/2110.07580)
- [KDD'2022-DosCond] Condensing graphs via one-step gradient matching. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539429?casa_token=gijVmZummzYAAAAA:nq1yIq5wN-sLT-qsLavBYyys3163tZNUB_3Hj7bOC6bkE4wP5BHZEcf-faFnk5djxCujlvTLQ3BSnlc)
- [NeurIPS-Workshop'2022] Faster hyperparameter search on graphs via calibrated dataset condensation. [[paper]](https://openreview.net/pdf?id=wcbgjg0X7LJ)
- [arXiv'2023-SFGC] Structure-free graph condensation: From large-scale graphs to condensed graph-free data. [[paper]](https://arxiv.org/pdf/2306.02664)
#### Graph Data Augmentation
- [ACM SIGKDD Explorations Newsletter'2022-Survey]  Data augmentation for deep graph learning: A survey. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3575637.3575646?casa_token=RTnILzVw3x4AAAAA:la46qhiVu6kPiJ1k4dopSZTYb0iA4oo2r8sIEXSGUUkoTW5byrlx-9VVf5-OOkoc0cDfcC-GOYpzc2k)
- [arXiv'2202-Survey] Graph data augmentation for graph machine learning: A survey. [[paper]](https://arxiv.org/pdf/2202.08871)
- [ICLR'2020-DropEdge] DropEdge: Towards deep graph convolutional networks on node classification. [[paper]](https://arxiv.org/pdf/1907.10903)
- [NeurIPS'2020-GRAND] Graph random neural networks for semi-supervised learning on graphs. [[paper]](https://proceedings.neurips.cc/paper/2020/file/fb4c835feb0a65cc39739320d7a51c02-Paper.pdf)
- [AAAI'2022-NASA] Regularizing graph neural networks via consistency-diversity graph augmentations. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20307/20066)
- [KDD'2020-NodeAug] NodeAug: Semi-supervised node classification with data augmentation. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403063?casa_token=5O6rVP5WUNcAAAAA:39vUmeVOiby_U-6UC3f4_vw5YEox2awfj22tgTeoZMa8f2IPeQ0w-2x23QC8V9_nwSO2F8Y9tFVWUbY)
- [AAAI'2021-GAUG] Data augmentation for graph neural networks. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17315/17122)
- [AAAI'2021-GraphMix] Graphmix: Improved training of gnns for semi-supervised learning. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17203/17010)
- [WWW'2021-GraphMixup] Mixup for node and graph classification. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449796)
- [WSDM'2021-GraphSMOTE] Graphsmote: Imbalanced node classification on graphs with graph neural networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3437963.3441720)
- [CVPR'2022-FLAG] Robust optimization as data augmentation for large-scale graphs. [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Kong_Robust_Optimization_As_Data_Augmentation_for_Large-Scale_Graphs_CVPR_2022_paper.pdf)
- [ICML'2022-G-Mixup] G-mixup: Graph data augmentation for graph classification. [[paper]](https://proceedings.mlr.press/v162/han22c/han22c.pdf)
- [ICML'2022-LAGNN] Local augmentation for graph neural networks. [[paper]](https://proceedings.mlr.press/v162/liu22s/liu22s.pdf)

## How To Learn From Graph Data With Limited-availability and Low-quality? --Graph Data Exploitation
### Graph Self-supervised Learning
- [TKDE'2022-Survey] Graph self-supervised learning: A survey. [[paper]](https://ieeexplore.ieee.org/iel7/69/10113816/09770382.pdf?casa_token=ydQeuh-OkpYAAAAA:hFnyLT6NKFztPKkO47dh8cdQ49fm5Sal8jmpoxdz5a4jBXqbL08A3miB1Z2XfGkrGChYovXRyb2W)
- [arXiv'2016-GAE] Variational graph auto-encoders. [[paper]](https://arxiv.org/pdf/1611.07308.pdf%5D)
- [CIKM'2017-MGAE] MGAE: Marginalized graph autoencoder for graph clustering. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3132847.3132967?casa_token=JNQueyr_GKgAAAAA:7xzVsWp65NPw-I2MqMxV-OkI21tM6chr7nfSHdcihKJGaEL5IL3OFYD17uEXSCI4a4JS4wTFAsSshwI)
- [IJCAI'2018-ARGA] Adversarially regularized graph autoencoder for graph embedding. [[paper]](https://arxiv.org/pdf/1802.04407)
- [ICLR'2019-DGI] Deep graph infomax. [[paper]](https://arxiv.org/pdf/1809.10341)
- [ICML'2020-MVGRL] Contrastive multi-view representation learning on graphs. [[paper]](http://proceedings.mlr.press/v119/hassani20a/hassani20a.pdf)
- [NeurIPS'2020-GraphCL] Graph contrastive learning with augmentations. [[paper]](https://proceedings.neurips.cc/paper_files/paper/2020/file/3fe230348e9a12c13120749e3f9fa4cd-Paper.pdf)
- [arXiv'2020-PairwiseDistance/NodeProperty] Self-supervised learning on graphs: Deep insights and new direction. [[paper]](https://arxiv.org/pdf/2006.10141)
- [NeurIPS'2020-GROVER] Self-supervised graph transformer on large-scale molecular data. [[paper]](https://proceedings.neurips.cc/paper/2020/file/94aef38441efa3380a3bed3faf1f9d5d-Paper.pdf)
- [WWW'2020-GMI] Graph representation learning via graphical mutual information maximization. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3366423.3380112?casa_token=8_d4PlRfYmIAAAAA:uYIQuMXnOVCRWjFlpm3Q2TKpnR-wrMBM_-MRjnS7A_8F8oEqKR5IAK0mXX7bDcP3o9L3_hk_-3MWjn4)
- [ICML'2020] When does self-supervision help graph convolutional networks? [[paper]](http://proceedings.mlr.press/v119/you20a/you20a.pdf)
- [WWW'2021-GCA] Graph contrastive learning with adaptive augmentation. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449802?casa_token=J5uSGyBfZzgAAAAA:3ppijn_2zTmgQmUeVpULosGAFxH8EBDZQoupLyb_JMTUBdELSQ27XCKREpudR4rnwn1ZPGEwNkmm2mI)
- [ICML'2021-JOAO] Graph contrastive learning automated. [[paper]](http://proceedings.mlr.press/v139/you21a/you21a.pdf)
- [NeurIPS'2021-AD-GCL] Adversarial graph augmentation to improve graph contrastive learning. [[paper]](https://proceedings.neurips.cc/paper/2021/file/854f1fb6f65734d9e49f708d6cd84ad6-Paper.pdf)
- [KDD'2022-GraphMAE] GraphMAE: Self-supervised masked graph autoencoders. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539321)
- [Information Sciences'2022-S2GRL] A new self-supervised task on graphs: Geodesic distance prediction. [[paper]](https://www.sciencedirect.com/science/article/pii/S0020025522006375?casa_token=I1kGX3li2DYAAAAA:JoWLxh9juXpnsr9g1PY2J56GT5rFe2EcVEbLxVVkN0uiWHQ8rJuyS2UQQZ9Eg5a98RavqlGGUus)
- [ICLR'2022-AutoSSL] Automated self-supervised learning for graphs. [[paper]](https://arxiv.org/pdf/2106.05470)

### Graph Semi-supervised Learning
- [ICML'2003] Semi-supervised learning using gaussian fields and harmonic functions. [[paper]](https://cdn.aaai.org/ICML/2003/ICML03-118.pdf)
- [NeurIPS'2003] Learning with local and global consistency. [[paper]](https://proceedings.neurips.cc/paper/2003/file/87682805257e619d49b8e0dfdc14affa-Paper.pdf)
- [ICML'2005] Learning from labeled and unlabeled data on a directed graph. [[paper]](https://dl.acm.org/doi/pdf/10.1145/1102351.1102482?casa_token=nvP_3IHEcZgAAAAA:rWVcWavK2RWe4SBAlQTZlW0oaAJV91Y-d6QX3K161YKOyaSYHdJk_Bz1482do0ybB16auyTsFNMbUO8)
- [AAAI'2018] Deeper insights into graph convolutional networks for semi-supervised learning. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/11604/11463)
- [KDD'2020-NodeAug] NodeAug: Semi-supervised node classification with data augmentation. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403063?casa_token=5O6rVP5WUNcAAAAA:39vUmeVOiby_U-6UC3f4_vw5YEox2awfj22tgTeoZMa8f2IPeQ0w-2x23QC8V9_nwSO2F8Y9tFVWUbY)
- [NeurIPS'2020-GRAND] Graph random neural networks for semi-supervised learning on graphs. [[paper]](https://proceedings.neurips.cc/paper/2020/file/fb4c835feb0a65cc39739320d7a51c02-Paper.pdf)
- [AAAI'2020-M3S] Multi-stage self-supervised learning for graph convolutional networks on graphs with few labeled nodes. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/6048/5904)
- [WSDM'2021-SimP-GCN] Node similarity preserving graph convolutional networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3437963.3441735)
- [ACM-TIS'2021-GCN-LPA] Combining graph convolutional neural networks and label propagation. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3490478?casa_token=PmUrlevC108AAAAA:KDwh2PRvk-k_1XmmD0KtZhlIyG7GUUzw1pYJe4fCHVKh6JL0Tl6IFRdg0DXpKunxc4-XYBysIUEdU0E)
- [AAAI'2021-CG3] Contrastive and generative graph convolutional networks for graph-based semi-supervised learning. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17206/17013)
- [NeurIPS'2021-GCPN] Contrastive graph poisson networks: Semi-supervised learning with extremely limited labels. [[paper]](https://proceedings.neurips.cc/paper/2021/file/31c0b36aef265d9221af80872ceb62f9-Paper.pdf)
- [AAAI'2022-Meta-PN] Meta propagation networks for graph few-shot semi-supervised learning. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20605/20364)
- [World Wide Web'2022-CycProp] Cyclic label propagation for graph semi-supervised learning. [[paper]](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s11280-021-00906-2&casa_token=y5doXTXXcdQAAAAA:FBx5NfHPBmJEjeSSjdTtJ-RfdEq57KqFn-fNqyQP-364LUhUxBEKGd_GHqQ2p9Hme8P1OnVuBWCFK42aBUA)

### Graph Active Learning
- [arXiv'2017-AGE] Active learning for graph embedding. [[paper]](https://arxiv.org/pdf/1705.05085)
- [IJCAI'2018-ANRMAB] Active discriminative network representation learning. [[paper]](https://opus.lib.uts.edu.au/bitstream/10453/131527/1/Active%20discriminative%20network%20representation%20learning.pdf)
- [IJCAI'2019-ActiveHNE] ActiveHNE: active heterogeneous network embedding. [[paper]](https://arxiv.org/pdf/1905.05659)
- [arXiv'2019-FeatProp] Active learning for graph neural networks via node feature propagation. [[paper]](https://arxiv.org/pdf/1910.07567)
- [WWW'2020-ATNE] Active domain transfer on network embedding. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3366423.3380024?casa_token=FecoeNTSq2QAAAAA:BzlicC0uYb8kyV8FgxwwGWg5V3G9DRb8cnATqEG_TURzQUKCIZYcF83JuQ0Jl14Y-EUXIygS0UAaDyI)
- [KDD'2020-ASGN] ASGN: An active semi-supervised graph neural network for molecular property prediction. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403117?casa_token=QSPH_GxeKq8AAAAA:GCbb1_8dboX0xxf94atEz2iBRtxb_RtuLWOaHYZW9hbfkojnPwhUN0U2LSMOxfYoAiw1BkMXoKsyjgI)
- [NeurIPS'2020-GPA] Graph policy network for transferable active learning on graphs. [[paper]](https://proceedings.neurips.cc/paper/2020/file/73740ea85c4ec25f00f9acbd859f861d-Paper.pdf)
- [ACML'2020-MetAL] Metal: Active semi-supervised learning on graphs via meta-learning. [[paper]](http://proceedings.mlr.press/v129/madhawa20a/madhawa20a.pdf)
- [TNNLS'2020-SEAL] Seal: Semisupervised adversarial active learning on attributed graphs. [[paper]](https://ieeexplore.ieee.org/iel7/5962385/6104215/09158558.pdf?casa_token=E_ZvrdYJhakAAAAA:0gkVyZk9eCLyBj7U04Z1_HBmA8LBZtZ4KtdwxUdY4Nl6wXCGB8i4ZRxyi0rEShdk3swoEVwijf8X)
- [VLDB Endowment'2021-GRAIN] GRAIN: improving data efficiency of graph neural networks via diversified in fluence maximization. [[paper]](https://arxiv.org/pdf/2108.00219)
- [NeurIPS'2021-RIM] RIM: Reliable influence-based active learning on graphs. [[paper]](https://proceedings.neurips.cc/paper/2021/file/eb86d510361fc23b59f18c1bc9802cc6-Paper.pdf)
- [WWW'2021-Attent] Attent: Active attributed network alignment. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449886?casa_token=IfxcTs5UUWgAAAAA:pJ-lyCKpCf1Jc3Kr7GG-JVWqYPH9jDYJjEwMa-3W-woQYcop5H3Zx264KGy3vCJ2EJU_WqAk2EH-RQI)
- [ICMD'2021-ALG] ALG: Fast and accurate active learning framework for graph convolutional networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3448016.3457325?casa_token=mvig94UQ6ngAAAAA:vU5pYuZ6WohLXhjiaCsuthFrGhPwqH4lYRDRLYjtXeiPb1_rvscz04dBZIZhGg4gX3mon6rFz1Xs6hs)
- [WWW'2022-ALLIE] ALLIE: Active learning on large-scale imbalanced graphs. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512229)
- [AAAI'2022-BIGENE] Batch active learning with graph neural networks via multi-agent deep reinforcement learning. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20897/20656)
- [ICLR'2022-IGP] Information Gain Propagation: A new way to graph active learning with soft labels. [[paper]](https://arxiv.org/pdf/2203.01093)
- [KDD'2022-JuryGCN] JuryGCN: quantifying jackknife uncertainty on graph convolutional networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539286?casa_token=pMOGKpsGGzwAAAAA:-hnHQLGfe7DXEX9DtkVcKC-t_RnRICOjtK9uXDAc_4GULkfy_l0AgGveJw9fGntKT3WivfcfeaKmwhk)
### Graph Transfer Learning
- [IJCAI'2019-DANE] DANE: domain adaptive network embedding. [[paper]](https://arxiv.org/pdf/1906.00684)
- [WWW'2020-UDA-GCN] Unsupervised domain adaptive graph convolutional networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3366423.3380219?casa_token=fswpPMwhRoUAAAAA:YGi0Ah4-jcilsyQn0FT-NG4XVwS3iTk8WXp30RiyP2rbeS7qdFiLEMF-3AQ1rFYHtJMNp-1L_QDCvOU)
- [AAAI'2020-ACDNE] Adversarial deep network embedding for cross-network node classification. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5692/5548)
- [ICDM'2020-OpenWGL] Openwgl: Open-world graph learning. [[paper]](https://ieeexplore.ieee.org/iel7/9338245/9338248/09338284.pdf?casa_token=R6FDgOWers4AAAAA:aBaB05Ecwql1oUk3CarNCI1TSGDb_9cVfjBft-TH1v4hvnoEhwWcEiEu2cw0VKQCgXxAeldEFDiH)
- [ICML'2020-PGL] Progressive graph learning for open-set domain adaptation. [[paper]](http://proceedings.mlr.press/v119/luo20b/luo20b.pdf)
- [NeurIPS'2021-SRGNN] Shift-robust gnns: Overcoming the limitations of localized graph training data. [[paper]](https://proceedings.neurips.cc/paper_files/paper/2021/file/eb55e369affa90f77dd7dc9e2cd33b16-Paper.pdf)
- [arXiv'2021-SOGA] Source free unsupervised graph domain adaptation. [[paper]](https://arxiv.org/pdf/2112.00955)
- [arXiv'2021] Graph domain adaptation: A generative view. [[paper]](https://arxiv.org/pdf/2106.07482)
- [NeurIPS-Workshop'2022-SRNC] Shift-robust node classification via graph clustering co-training. [[paper]](https://openreview.net/pdf?id=CXm7uzRlvxf)

## How To Build Graph MLOps System: The Graph Data-centric View.  --Graph Data Collection, Exploration, Maintenance
### Graph Data Collection
- Amazon Mechanical Turk: https://www.mturk.com/
- [SIGIR-Workshop'2011] Semi-supervised consensus labeling for crowdsourcing. [[paper]](https://www.ischool.utexas.edu/~ml/papers/tang-cir11.pdf)
- [Cloud Computing'2021] Knowledge graphs meet crowdsourcing: a brief survey. [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-69992-5_1)
- [Journal of Classification'1997] Estimation and prediction for stochastic blockmodels for graphs with latent block structure. [[paper]](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1007/s003579900004.pdf&casa_token=HmfwBFmsgzwAAAAA:m_PjqmuzWqzS3EWaOvjQD6BN-oNlQ-N3Wiie67xOvRqhaBVsKcmgreLA8w17PJU3B2QRzIeNSM8o4N3UhQ8)
- Probabilistic graphical models: principles and techniques. [[book]](https://list01.bio.ens.psl.eu/wws/d_read/machine_learning/BayesianNetworks/koller.pdf)
- [NeurIPS'2019] Gnnexplainer: Generating explanations for graph neural networks. [[paper]](https://proceedings.neurips.cc/paper_files/paper/2019/file/d80b7040b773199015de6d3b4293c8ff-Paper.pdf)
- [KDD'2014] Focused clustering and outlier detection in large attributed graphs. [[paper]](https://dl.acm.org/doi/pdf/10.1145/2623330.2623682?casa_token=bFPgGTyUJrwAAAAA:UxQuO_EC7-SHHC3CPnBlhi04YtzUhiwQ2FSS29OMhdIBz3Wq0WVoSDgNtwM06cKifzqFOH2bj_DJc_g)
- [Journal of Machine Learning Research'2023] Graph clustering with graph neural networks. [[paper]](https://www.jmlr.org/papers/volume24/20-998/20-998.pdf)
- [WWW'2021] Pathfinder discovery networks for neural message passing. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449882?casa_token=OeRAWAYACGkAAAAA:KcUEIrMuvK8IwYpfQeXKoSWnL2ibQYXzke4bL_-bEBljWWIojJMNy_sPtEtBmIl2I942D4R19UpsHn8)
- [arXiv'2020] Benchmarking graph neural networks. [[paper]](https://www.jmlr.org/papers/volume24/22-0567/22-0567.pdf)
- [arXiv'2022] Synthetic graph generation to benchmark graph learning. [[paper]](https://arxiv.org/pdf/2204.01376)
- [KDD'2022] Graphworld: Fake graphs bring real insights for gnns. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539203)
### Graph Data Exploration
- NetworkX: https://networkx.org/
- igraph: https://igraph.org/
- Neo4j: https://neo4j.com/
- [ECML-PKDD'2021] Graphsvx: Shapley value explanations for graph neural networks. [[paper]](https://arxiv.org/pdf/2104.10482)
### Graph Data Maintenance
- [arXiv'2022-TrustworthyGNN-Survey] Trustworthy graph neural networks: Aspects, methods and trends. [[paper]](https://arxiv.org/pdf/2205.07424)
- [IEEE Network'2010] Privacy and security for online social networks: challenges and opportunities. [[paper]](https://ieeexplore.ieee.org/iel5/65/5510907/05510913.pdf?casa_token=--aFnZdnJPMAAAAA:GY_7DMBORUJ5xD6NmiEDLdSQyCv7BTjuFZy3RY3LGF53EIiTYf7BB_0oKbfGOQPjq4OkD7drRZNs)
- [SIGMOD'2008] Towards identity anonymization on graphs. [[paper]](https://dl.acm.org/doi/pdf/10.1145/1376616.1376629?casa_token=-rPE_pQvmwAAAAAA:equ17IAF6blOiwP0ke0qTz8l4pRE9hYUvjG8ONxpO-OFyV3yAWSkIAuEw-yBOlsC89hWmcoCiP7U9qo)
- [Multimedia Tools and Applications'2018] Privacy preservation based on clustering perturbation algorithm for social network. [[paper]](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s11042-017-5502-3&casa_token=ExB8rAhIa0gAAAAA:T0OZ9Se-h1YcuxwT_PifyHTa_sfvE9x884x0T5mAcoGikV8gn_WBIG-EZ9wulZSxSFqa4a0H98hJW1JUXIk)
- [EDBT/ICDT Workshops'2015] Privacy-Integrated Graph Clustering Through Differential Privacy. [[paper]](https://www.academia.edu/download/77577505/EDBTICDT-WS2015-complete.pdf#page=252)
- [Information Sciences'2020] PGAS: Privacy-preserving graph encryption for accurate constrained shortest distance queries. [[paper]](https://www.sciencedirect.com/science/article/pii/S0020025519306991?casa_token=tpKpvhkxlcYAAAAA:FWf7bFBr-nQ90BMOgKaeZGdMk7bA6BdbONNtfCEde5uNb8FvM8Wqlpq1zKlzZLcH4vZrd53onoE)
- [KDD'2022] Federatedscope-gnn: Towards a unified, comprehensive and efficient package for federated graph learning. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539112?casa_token=lLfb0irOvVcAAAAA:peP_OcLHTBrw8vOr-vdfk6ZtcBCzDpxPW_MpyQm9joQg1awXqso9xQYCCdwu0ioNqOFbhgv4dOmSoTw)
- [AAAI'2023] Federated learning on Non-IID graphs via structural knowledge sharing. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/26187/25959)
- [IEEE Communications Magazine'1994] Access control: principle and practice. [[paper]](https://ieeexplore.ieee.org/iel1/35/7577/00312842.pdf?casa_token=ue7Oix7c3DwAAAAA:xvf-oW5BVRFKhutUkmBaEc2MqiMSN0yW9yuY7WzHrblUkaZ9fKZziY9BwOzlATnLgFPBHvtZ0FF7)
- [Global Summit on Computer and Information Technology'2014] Implementation of elliptic curve digital signature algorithm (ECDSA). [[paper]](https://www.researchgate.net/profile/Abdessalem-Abidi/publication/286584272_Implementation_of_elliptic_curve_digital_signature_algorithm_ECDSA/links/570b712e08ae8883a1fe0f70/Implementation-of-elliptic-curve-digital-signature-algorithm-ECDSA.pdf)
- [Computers and Security'2021] Threat detection and investigation with system-level provenance graphs: a survey. [[paper]](https://www.sciencedirect.com/science/article/pii/S0167404821001061?casa_token=2AkT5nELWYMAAAAA:nczh2dVDq2nc9mSMJaOo9VjPod7g4BTqHYV-pzzC0UA_eZjRpEhvL1wDaAVRJ7uxwqAn8bnTszQ)
### Graph MLOps
- Kubeflow: https://github.com/kubeflow/kubeflow
- Amazon SageMaker: https://aws.amazon.com/sagemaker/
- Amazon Neptune: https://neptune.ai/product
- GraphStorm: https://github.com/awslabs/graphstorm/wiki
- Real-time Fraud Detection with Graph Neural Network on DGL: https://github.com/awslabs/realtime-fraud-detection-with-gnn-on-dgl
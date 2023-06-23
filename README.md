# Awesome-Data-Centric-GraphML
A collection of papers and resources about Data Centric Graph Machine Learning (DC-GML)



## Graph Data-Centric Tasks
### Structure-based tasks
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
### Feature-based tasks
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
### Label-based tasks
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
- [arXiv；2022-TopoImb] TopoImb: Toward topology-level imbalance in learning from graphs. [[paper]](https://arxiv.org/pdf/2212.08689)
- [IJCAI'2013-igBoost] Graph classification with imbalanced class distributions and noise. [[paper]](https://www.researchgate.net/profile/Shirui-Pan-3/publication/262204599_Graph_classification_with_imbalanced_class_distributions_and_noise/links/564bc59d08ae3374e5dddb5b/Graph-classification-with-imbalanced-class-distributions-and-noise.pdf)
- [CIKM'2022-G2GNN] Imbalanced graph classification via graph-of-graph neural networks. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557356?casa_token=gzP3pWpfsWMAAAAA:BPdp0A0Mh3tWlXo6i4Mvd5kfVo0geTqqfH_hOyCpAki9krAMdq6fZKCScHffiQdfq9mZSPYBRR85uL4)

## Graph Data-Centric Learning Paradigms

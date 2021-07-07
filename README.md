Summary about tensor network in machine learning.

## Workshop

* [**IJCAL**](https://tensorworkshop.github.io/2020/index.html): International Workshop on Tensor Network Representations in Machine Learning
* [**NeurIPS2020**](https://tensorworkshop.github.io/NeurIPS2020/): Quantum tensor networks in machine learning
* [ipam](http://ipam.ucla.edu/wp-content/uploads/2019/09/TMWS2-Poster.pdf): Tensor Network States and Applications, **APRIL 19 - 23, 2021**

## Learning Materials

* [TN_tutorial](https://github.com/ranshiju/TN_tutorial)是冉仕举老师对张量网络机器学习的一个详细的介绍，该仓库是[Bilibili视频](https://www.bilibili.com/video/BV17z411i7yM?p=1)的配套代码，搭配食用效果更佳。
* [**Tensors**.net](https://www.tensors.net/)是一个开源的网站，里面图解了各种张量网络算法，并给出了Python/Matlab/Julia的相关实现，简直良
* [Tensor Networks](https://paperswithcode.com/task/tensor-networks)提供了一些张量网络机器学习的视频、论文以及对应代码，也是做了于本仓库类似的内容，推荐大家结合代码去学习，事半功倍！
* [awesome-quantum-machine-learning](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning)包含了全网所有的量子机器学习基础知识，算法，研究材料，项目以及项目描述，例如**量子遗传算法、量子隐马尔可夫模型、基于主成分分析的量子分类算法**等等，有很多比较**前沿的工作**在里面。
* [tensornetwork.org](https://tensornetwork.org/)张量网络算法、理论和软件的介绍

## **Tensor network library**

大部分张量网络收缩库都是基于Python，还有少量的C++、Matlab，在下面会注明

* [TensorNetwork](https://github.com/google/TensorNetwork)，Google于2019年开源的Python库，目前应用最为广泛
* [qml](https://github.com/qmlcode/qml)是用于量子机器学习的Python工具包，有回归、预测、学习曲线等等，能省很多功夫去造轮子
* [netket](https://github.com/netket/netket)是一个开源代码项目，它提供了用于通过ANN和ML研究多体量子系统的前沿方法，它是基于JAX构建的Python库。
* [tenpy](https://github.com/tenpy/tenpy) Python库，用于模拟具有张量网络的高度相关的量子系统，有比较详细的文档和算法演示示例（例如TEBD和DMRG）
* [PyQPanda](https://github.com/OriginQ/QPanda-2)是**本源量子**开发的量子计算编程框架，提供了详细的文档和量子算法介绍，能够通过线路模拟算法。
* [tncontract](https://github.com/andrewdarmawan/tncontract) Python的开源张量网络库，比较小众，采用Numpy库做为后端，包含很多用于一维和二维张量网络的算法。
* [TNML(**C++**)](https://github.com/emstoudenmire/TNML)  出自大佬[emstoudenmire](https://github.com/emstoudenmire/TNML/commits?author=emstoudenmire)之手
* [ITensor(C++)](https://github.com/ITensor/ITensor) 高效的张量网络计算库，提供了相关文档

## Survery（Updating...）


### 2016
* Supervised Learning with Quantum-Inspired Tensor Networks [[Code]](https://github.com/emstoudenmire/TNML)
  * E.M. Stoudenmire et al. (NIPS 2016)

### 2018
* Tensorizing generative adversarial nets [[Paper]](https://ieeexplore.ieee.org/abstract/document/8552122) [[Code]](https://github.com/xwcao/TGAN)
  * X. Cao, X. Zhao, Q. Zhao. [C] (ICCE Asia 2018 (International Conference On Consumer Electronics))
* Generative adversarial positive-unlabeled learning [[Paper]](https://www.ijcai.org/proceedings/2018/0312.pdf) [[Code]](https://qibinzhao.github.io/publications/IJCAI_2018_HouMing/gen_pu_demo.zip)
  * M. Hou, B. Chaib-draa, C. Li, Q. Zhao. [C] (IJCAI 2018)
* Unsupervised Generative Modeling Using Matrix Product States [[arXiv]](https://arxiv.org/abs/1709.01662) [[Code]](https://github.com/congzlwag/UnsupGenModbyMPS) 
  * Zhao-Yu Han et al. (PRX 2018)

### 2019
* Machine Learning by Two-Dimensional Hierarchical Tensor Networks: A Quantum Information Theoretic Perspective on Deep Architectures [[arXiv]](https://arxiv.org/abs/1710.04833) [[Github]](https://github.com/dingliu0305/Tree-Tensor-Networks-in-Machine-Learning)
  * Ding Liu et al. (NJP 2019)

### 2020
* Generative tensor network classification model for supervised machine learning [[arXiv]](https://arxiv.org/abs/1903.10742) [[Code]](https://github.com/crazybigcat/GTNC)
  * Zheng-Zhi Sun, et al. (PRB 2020)
* Tangent-Space Gradient Optimization of Tensor Network for Machine Learning  [[arXiv]](https://arxiv.org/abs/2001.04029) [[Code]](https://github.com/crazybigcat/TSGO)
  * Zheng-Zhi Sun, et al. (PRE 2020)
* Multi-layered tensor networks for image classification [[arXiv]](https://arxiv.org/abs/2011.06982) [[Code]](https://github.com/raghavian/mltn)
  * Raghavendra Selvan et al. (NeurIPS 2020)
* Quantum Tensor Network in Machine Learning: An Application to Tiny Object Classification [[arXiv]](https://arxiv.org/pdf/2101.03154.pdf) [[Code]](https://github.com/timqqt/MERA_Image_Classification)
  * Fanjie Kong et al. (NeurIPS 2020)
* Tensor Networks for Medical Image Classification [[Code]](https://github.com/raghavian/loTeNet_pytorch/)
  * Raghavendra Selvan et al. (MIDL 2020) 
* Deep convolutional tensor network [[arXiv]](https://arxiv.org/abs/2005.14506) [[Code]](https://github.com/philip-bl/dctn)
  * Philip Blagoveschensky et al. (Preprint. Under review 2020)
* Evolutionary Topology Search for Tensor Network Decomposition [[Paper]](http://proceedings.mlr.press/v119/li20l/li20l.pdf) [[Code]](https://github.com/minogame/icml2020-TNGA)
  * C. Li, Z. Sun. [C] (ICML 2020)

### 2021
* Fully-Connected Tensor Network Decomposition and Its Application to Higher-Order Tensor Completion [[Paper]](https://www.aaai.org/AAAI21Papers/AAAI-4990.ZhengY.pdf) [[Code]](https://qibinzhao.github.io/publications/AAAI2021_Yu_Bang_Zheng/code_FCTN_Decomposition.zip)
  * Y. Zheng, T. Huang, X. Zhao, Q. Zhao, T. Jiang (AAAI 2021)
* Locally orderless tensor networks for classifying two- and three-dimensional medical images [[Paper]]() [[Code]](https://github.com/raghavian/LoTeNet_pytorch/)
  * Raghavendra Selvan, et, al. (MELBA 2021)
* Quantum-Classical Machine learning by Hybrid Tensor Networks [[arXiv]](https://arxiv.org/abs/2005.09428) [[Code]](https://github.com/dingliu0305/Hybrid-Tensor-Network)
  * Fanjie Kong et, al. (Preprint 2021)
* Tensor networks for unsupervised machine learning [[Paper]](https://arxiv.org/abs/2106.12974) [[Code]](https://github.com/bnuliujing/tn-for-unsup-ml)
  * Jing Liu et, al. (Preprint 2021)

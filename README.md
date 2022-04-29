# Dive into Federated Learning
Tutorials and paper lists for federated learning. 

Wish this can help you dive into FL more easily.

关于联邦学习的教程和论文列表。希望能方便大家入门联邦学习。

[toc]

## Tutorials 教程

- [NeurIPS 2020] Federated Learning Tutorial [[Web]](https://sites.google.com/view/fl-tutorial/) [[Slides]](https://drive.google.com/file/d/1QGY2Zytp9XRSu95fX2lCld8DwfEdcHCG/view) [[Video]](https://slideslive.com/38935813/federated-learning-tutorial)
- [联邦学习入门教程参考](https://docs.qq.com/doc/DVUxDVkd4b0FXdUpK)



## Survey 综述

- [ICLR-DPML 2021] FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks [[Paper]](https://arxiv.org/abs/2104.07145) [[Code]](https://github.com/FedML-AI/FedGraphNN)
- [arXiv 2021] Federated Graph Learning -- A Position Paper [[Paper]](https://arxiv.org/abs/2105.11099)
- [IEEE TKDE 2021] A Survey on Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection [[Paper]](https://arxiv.org/pdf/1907.09693.pdf?ref=https://githubhelp.com)
- [arXiv 2021] A Survey of Fairness-Aware Federated Learning [[Paper]](https://arxiv.org/abs/2111.01872)
- [Foundations and Trends in Machine Learning 2021] Advances and Open Problems in Federated Learning [[Paper]](https://arxiv.org/abs/1912.04977) [[Chinese Version]](https://xwzheng.gitbook.io/fl/) [[FL FAQ]](https://github.com/tao-shen/Federated-Learning-FAQ) 
- [arXiv 2020] Towards Utilizing Unlabeled Data in Federated Learning: A Survey and Prospective [[Paper]](https://arxiv.org/abs/2002.11545)
- [IEEE Signal Processing Magazine 2020] Federated Learning: Challenges, Methods, and Future Directions [[Paper]](https://arxiv.org/abs/1908.07873)
- [IEEE Communications Surveys & Tutorials 2020] Federated Learning in Mobile Edge Networks A Comprehensive Survey [[Paper]](https://arxiv.org/abs/1909.11875)
- [IEEE TIST 2019] Federated Machine Learning: Concept and Applications [[Paper]](https://arxiv.org/pdf/1902.04885.pdf)



## Frameworks 框架

- __FedLab:__ [Code](https://github.com/SMILELab-FL/FedLab), [FedLab-benchmarks](https://github.com/SMILELab-FL/FedLab-benchmarks), [Doc](https://fedlab.readthedocs.io/) ([zh-CN-Doc](https://fedlab.readthedocs.io/zh_CN/latest/)), [Paper](https://arxiv.org/abs/2107.11621)
- __Flower:__ [Code](https://github.com/adap/flower), [Homepage](https://flower.dev/), [Doc](https://flower.dev/docs/), [Paper](https://arxiv.org/abs/2007.14390)
- __FedML:__ [Code](https://github.com/FedML-AI/FedML), [Doc](http://doc.fedml.ai/#/), [Paper](https://arxiv.org/abs/2007.13518)
- __FedLearn:__ [Code](https://github.com/cyqclark/fedlearn-algo), [Paper](https://arxiv.org/abs/2107.04129)
- __PySyft:__ [Code](https://github.com/OpenMined/PySyft), [Doc](https://pysyft.readthedocs.io/en/latest/installing.html), [Paper](https://arxiv.org/abs/1811.04017)
- __TensorFlow Federated (TFF):__ [Code](https://github.com/tensorflow/federated), [Doc](https://www.tensorflow.org/federated)
- __FEDn:__ [Code](https://github.com/scaleoutsystems/fedn), [Paper](https://arxiv.org/abs/2103.00148)
- __FATE:__ [Code](https://github.com/FederatedAI/FATE), [Homepage](https://www.fedai.org/), [Doc](https://fate.readthedocs.io/en/latest/), [Paper](https://www.jmlr.org/papers/v22/20-815.html)
- __PaddleFL:__ [Code](https://github.com/PaddlePaddle/PaddleFL), [Doc](https://paddlefl.readthedocs.io/en/latest/index.html)
- __Fedlearner:__ [Code](https://github.com/bytedance/fedlearner)
- __OpenFL:__ [Code](https://github.com/intel/openfl), [Doc](https://openfl.readthedocs.io/en/latest/install.html), [Paper](https://arxiv.org/abs/2105.06413)



## Benchmarks 基准

- __FedLab-benchmarks:__ [Code](https://github.com/SMILELab-FL/FedLab-benchmarks)
- [ACM TIST 2022] The OARF Benchmark Suite: Characterization and Implications for Federated Learning Systems [[Code]](https://github.com/Xtra-Computing/OARF) [[Paper]](https://arxiv.org/abs/2006.07856)
- [IEEE ICDE 2022] Federated Learning on Non-IID Data Silos: An Experimental Study [[Paper]](https://arxiv.org/abs/2102.02079) [[Official Code]](https://github.com/Xtra-Computing/NIID-Bench) [[FedLab Tutorial]](https://fedlab.readthedocs.io/en/master/tutorials/dataset_partition.html)
- [ICLR-DPML 2021] FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks [[Paper]](https://arxiv.org/abs/2104.07145) [[Code]](https://github.com/FedML-AI/FedGraphNN)
- [arXiv 2018] LEAF: A Benchmark for Federated Settings [[Homepage]](https://leaf.cmu.edu/) [[Official tensorflow]](https://github.com/TalwalkarLab/leaf) [[Unofficial PyTorch]](https://github.com/SMILELab-FL/FedLab-benchmarks/tree/master/fedlab_benchmarks/leaf) [[Paper]](https://arxiv.org/abs/1812.01097)



## FL+Semi-supervised Learning 联邦半监督

- [ICLR 2021] Federated Semi-supervised Learning with Inter-Client Consistency & Disjoint Learning [[Paper]](https://arxiv.org/abs/2006.12097) [[Code]](https://github.com/wyjeong/FedMatch)
- [arXiv 2021] SemiFL: Communication Efficient Semi-Supervised Federated Learning with Unlabeled Clients [[Paper]](https://arxiv.org/abs/2106.01432)
- [IEEE BigData 2021] Improving Semi-supervised Federated Learning by Reducing the Gradient Diversity of Models [[Paper]](https://ieeexplore.ieee.org/abstract/document/9671693)
- [arXiv 2020] Benchmarking Semi-supervised Federated Learning [[Paper]](https://www.researchgate.net/profile/Yujun-Yan/publication/343903563_Benchmarking_Semi-supervised_Federated_Learning/links/5f571cb8299bf13a31aaff33/Benchmarking-Semi-supervised-Federated-Learning.pdf)] [[Code]](https://github.com/jhcknzzm/SSFL-Benchmarking-Semi-supervised-Federated-Learning)



## FL+HPC 联邦高性能计算

- [arXiv 2022] Sky Computing: Accelerating Geo-distributed Computing in Federated Learning [[Paper]](https://arxiv.org/abs/2202.11836) [[Code]](https://github.com/hpcaitech/SkyComputing) 
- [ACM HPDC 2020] TiFL: A Tier-based Federated Learning System [[Paper]](https://arxiv.org/abs/2001.09249) [[Video]](https://www.youtube.com/watch?v=y8GZKn2zyNk)



## Blogs 博客

- [无知者：联邦学习系统前沿](https://www.zhihu.com/column/c_1274126974563659776)
- [无知者：联邦学习开源框架FedLab相关](https://www.zhihu.com/column/c_1412167529406550016)
- [lokinko:联邦学习论文分享](https://www.zhihu.com/column/c_1274302650633465856)
- [AgentDS：划水运动员假装在学术](https://www.zhihu.com/column/c_1412459345045417984)



## Awesome List

- [lokinko/Federated-Learning](https://github.com/lokinko/Federated-Learning)
- [chaoyanghe/Awesome-Federated-Learning](https://github.com/chaoyanghe/Awesome-Federated-Learning)
- [weimingwill/awesome-federated-learning](https://github.com/weimingwill/awesome-federated-learning)
- [tushar-semwal/awesome-federated-computing](https://github.com/tushar-semwal/awesome-federated-computing)
- [ZeroWangZY/federated-learning](https://github.com/ZeroWangZY/federated-learning)
- [innovation-cat/Awesome-Federated-Machine-Learning](https://github.com/innovation-cat/Awesome-Federated-Machine-Learning)
- [huweibo/Awesome-Federated-Learning-on-Graph-and-GNN-papers](https://github.com/huweibo/Awesome-Federated-Learning-on-Graph-and-GNN-papers)

# awesome-graph-attack-papers
This repository aims to provide links to works about adversarial attacks and defenses on graph data or GNN (Graph Neural Networks).

### Contents

* [1. Survey Papers](#1-survey-papers)
* [2. Attack Papers](#2-attack-papers) (classified according to attack goal)
	* [2.1 Targeted Attack](#21-targeted-attack)
	* [2.2 Untargeted Attack](#22-untargeted-attack) 
* [3. Defense Papers](#3-defense-papers)
* [4. Certified Robustness Papers](#4-certified-robustness-papers)

## 1. Survey Papers
1. **Adversarial Attacks and Defenses on Graphs: A Review and Empirical Study.**
   *Wei Jin, Yaxin Li, Han Xu, Yiqi Wang, Jiliang Tang.*  arxiv, 2020. [[paper]](https://arxiv.org/abs/2003.00653) [[code]](https://github.com/DSE-MSU/DeepRobust/)
1. **Adversarial Attacks and Defenses in Images, Graphs and Text: A Review.**
   *Han Xu, Yao Ma, Haochen Liu, Debayan Deb, Hui Liu, Jiliang Tang, Anil K. Jain.* arxiv, 2019. [[paper]](https://arxiv.org/pdf/1909.08072.pdf)
1. **Adversarial Attack and Defense on Graph Data: A Survey.**
*Lichao Sun, Ji Wang, Philip S. Yu, Bo Li.* arviv 2018. [[paper]](https://arxiv.org/pdf/1812.10528.pdf) 

## 2. Attack Papers
### 2.1 Targeted Attack
1. **MGA: Momentum Gradient Attack on Network.**
*Jinyin Chen, Yixian Chen, Haibin Zheng, Shijing Shen, Shanqing Yu, Dan Zhang, Qi Xuan.* [[paper]](Jinyin Chen, Yixian Chen, Haibin Zheng, Shijing Shen, Shanqing Yu, Dan Zhang, Qi Xuan)
1. **Graph Universal Adversarial Attacks: A Few Bad Actors Ruin Graph Learning Models.** 
   *Xiao Zang, Yi Xie, Jie Chen, Bo Yuan.* arxiv, 2020. [[paper]](https://arxiv.org/abs/2002.04784)
1. **Time-aware Gradient Attack on Dynamic Network Link Prediction.** 
   *Jinyin Chen, Jian Zhang, Zhi Chen, Min Du, Feifei Li, Qi Xuan.* arxiv 2019. [[paper]](https://arxiv.org/pdf/1911.10561.pdf)
1. **Multiscale Evolutionary Perturbation Attack on Community Detection.** 
   *Jinyin Chen, Yixian Chen, Lihong Chen, Minghao Zhao, and Qi Xuan.* arxiv 2019. [[paper]](https://arxiv.org/pdf/1910.09741.pdf)
1. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.**
   *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.* IJCAI 2019. [[paper]](https://arxiv.org/pdf/1903.01610.pdf) [[code]](https://github.com/DSE-MSU/DeepRobust)
1. **Data Poisoning Attack against Knowledge Graph Embedding.**
*Hengtong Zhang, Tianhang Zheng, Jing Gao, Chenglin Miao, Lu Su, Yaliang Li, Kui Ren.* IJCAI 2019. [[paper]](https://arxiv.org/pdf/1904.12052.pdf)
1. **Attacking Graph-based Classification via Manipulating the Graph Structure.**
*Binghui Wang, Neil Zhenqiang Gong.* CCS 2019. [[paper]](https://arxiv.org/pdf/1903.00553.pdf)
1. **A Restricted Black-box Adversarial Framework Towards Attacking Graph Embedding Models.** 
   *Heng Chang, Yu Rong, Tingyang Xu, Wenbing Huang, Honglei Zhang, Peng Cui, Wenwu Zhu, Junzhou Huang.* AAAI 2020. [[paper]](https://arxiv.org/pdf/1908.01297.pdf) [[code]](https://github.com/SwiftieH/GFAttack)
1. **Adversarial Attacks on Node Embeddings via Graph Poisoning.** 
   *Aleksandar Bojchevski, Stephan Günnemann.* ICML 2019. [[paper]](https://arxiv.org/pdf/1809.01093.pdf) [[code]](https://github.com/abojchevski/node_embedding_attack)
1. **Adversarial Attack on Graph Structured Data.**
   *Hanjun Dai, Hui Li, Tian Tian, Xin Huang, Lin Wang, Jun Zhu, Le Song.* ICML 2018. [[paper]](https://arxiv.org/pdf/1806.02371.pdf) [[code]](https://github.com/Hanjun-Dai/graph_adversarial_attack)
1. **Fast Gradient Attack on Network Embedding.**
*Jinyin Chen, Yangyang Wu, Xuanheng Xu, Yixian Chen, Haibin Zheng, Qi Xuan.* arxiv 2018. [[paper]](https://arxiv.org/pdf/1809.02797.pdf) [[code]](https://github.com/DSE-MSU/DeepRobust)
1. **Adversarial Attacks on Neural Networks for Graph Data.**
   *Daniel Zügner, Amir Akbarnejad, Stephan Günnemann.*  KDD 2018. [[paper]](https://arxiv.org/pdf/1805.07984.pdf) [[code]](https://github.com/danielzuegner/nettack)

### 2.2 Untargeted Attack
1. **Node Injection Attacks on Graphs via Reinforcement Learning.** 
   *Yiwei Sun, Suhang Wang, Xianfeng Tang, Tsung-Yu Hsieh, Vasant Honavar.* WWW 2020. [[paper]](https://arxiv.org/pdf/1909.06543.pdf)
1. **A Unified Framework for Data Poisoning Attack to Graph-based Semi-supervised Learning.** 
   *Xuanqing Liu, Si Si, Xiaojin(Jerry) Zhu, Yang Li, Cho-Jui Hsieh.* NeurIPS 2019. [[paper]](https://arxiv.org/pdf/1910.14147.pdf)
1. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.**
   *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.* IJCAI 2019. [[paper]](https://arxiv.org/pdf/1903.01610.pdf) [[code]](https://github.com/DSE-MSU/DeepRobust)
1. **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective.** 
   *Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, Xue Lin.* ICJAI 2019. [[paper]](https://arxiv.org/pdf/1906.04214.pdf) [[code]](https://github.com/KaidiXu/GCN_ADV_Train)
1. **Adversarial Attacks on Node Embeddings via Graph Poisoning.** 
   *Aleksandar Bojchevski, Stephan Günnemann.* ICML 2019. [[paper]](https://arxiv.org/pdf/1809.01093.pdf) [[code]](https://github.com/abojchevski/node_embedding_attack)
1. **Adversarial Attacks on Graph Neural Networks via Meta Learning.**
   *Daniel Zugner, Stephan Gunnemann.* ICLR 2019. [[paper]](https://openreview.net/pdf?id=Bylnx209YX) [[code]](https://github.com/danielzuegner/gnn-meta-attack)
1. **Attacking Graph Convolutional Networks via Rewiring.**
   *Yao Ma, Suhang Wang, Lingfei Wu, Jiliang Tang.*  arxiv 2019. [[paper]](https://arxiv.org/pdf/1906.03750.pdf)


## 3. Defense Papers
1. **How Robust Are Graph Neural Networks to Structural Noise?**
*James Fox, Sivasankaran Rajamanickam.* arxiv 2020. [[paper]](https://arxiv.org/pdf/1912.10206.pdf)
1. **GraphDefense: Towards Robust Graph Convolutional Networks.**
   *Xiaoyun Wang, Xuanqing Liu, Cho-Jui Hsieh.*  arxiv 2019. [[paper]](https://arxiv.org/pdf/1911.04429v1.pdf)
1. **All You Need is Low (Rank): Defending Against Adversarial Attacks on Graphs.**
   *Negin Entezari, Saba Al-Sayouri, Amirali Darvishzadeh, and Evangelos E. Papalexakis.*  WSDM 2020. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3336191.3371789?download=true) [[code]](https://github.com/DSE-MSU/DeepRobust/)
1. **Graph Adversarial Training: Dynamically Regularizing Based on Graph Structure**
   *Fuli Feng, Xiangnan He, Jie Tang, Tat-Seng Chua.*  TKDE 2019. [[paper]](https://arxiv.org/pdf/1902.08226.pdf)
1. **Edge Dithering for Robust Adaptive Graph Convolutional Networks.**
   *Vassilis N. Ioannidis, Georgios B. Giannakis.*  arxiv 2019. [[paper]](https://arxiv.org/pdf/1910.09590.pdf)   
1. **GraphSAC: Detecting anomalies in large-scale graphs.**
   *Vassilis N. Ioannidis, Dimitris Berberidis, Georgios B. Giannakis.* arxiv 2019. [[paper]](https://arxiv.org/pdf/1910.09589.pdf)
1. **Robust Graph Neural Network Against Poisoning Attacks via Transfer Learning.**
   *Xianfeng Tang, Yandong Li, Yiwei Sun, Huaxiu Yao, Prasenjit Mitra, Suhang Wang.*  WSDM 2020. [[paper]](https://arxiv.org/pdf/1908.07558.pdf)
1. **Robust Graph Convolutional Networks Against Adversarial Attacks.**
   *Dingyuan Zhu, Ziwei Zhang, Peng Cui, Wenwu Zhu.*  KDD 2019. [[paper]](http://pengcui.thumedialab.com/papers/RGCN.pdf) 
1. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.**
   *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.*   IJCAI 2019. [[paper]](https://arxiv.org/pdf/1903.01610.pdf) [[code]](https://github.com/DSE-MSU/DeepRobust)
1. **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective.**
   *Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, Xue Lin.*  ICJAI 2019. [[paper]](https://arxiv.org/pdf/1906.04214.pdf) [[code]](https://github.com/KaidiXu/GCN_ADV_Train)
1. **Power up! Robust Graph Convolutional Network against Evasion Attacks based on Graph Powering.**
   *Ming Jin, Heng Chang, Wenwu Zhu, Somayeh Sojoudi.*  arxiv 2019. [[paper]](https://arxiv.org/abs/1905.10029)
1. **Latent Adversarial Training of Graph Convolution Networks.**
   *Hongwei Jin, Xinhua Zhang.*  ICML 2019 workshop. [[paper]](https://graphreason.github.io/papers/35.pdf)
1. **Batch Virtual Adversarial Training for Graph Convolutional Networks.**
   *Zhijie Deng, Yinpeng Dong, Jun Zhu.*  ICML 2019 Workshop. [[paper]](https://arxiv.org/pdf/1902.09192.pdf)
1. **Graph Adversarial Training: Dynamically Regularizing Based on Graph Structure.**
   *Fuli Feng, Xiangnan He, Jie Tang, Tat-Seng Chua.*   arXiv, 2019. [[paper]](https://arxiv.org/pdf/1902.08226.pdf)

## 4. Certified Robustness Papers
1. **Certified Robustness of Community Detection against Adversarial Structural Perturbation via Randomized Smoothing.**
*Jinyuan Jia, Binghui Wang, Xiaoyu Cao, Neil Zhenqiang Gong.* WWW 2020. [[paper]](https://arxiv.org/pdf/2002.03421.pdf)
1. **Certifiable Robustness to Graph Perturbations.**
   *Aleksandar Bojchevski, Stephan Günnemann.*  NeurIPS 2019. [[paper]](https://arxiv.org/pdf/1910.14356.pdf)[[code]](https://github.com/abojchevski/graph_cert)
1. **Certifiable Robustness and Robust Training for Graph Convolutional Networks.**
   *Daniel Zügner Stephan Günnemann.*  KDD 2019. [[paper]](https://arxiv.org/pdf/1906.12269.pdf) [[code]](https://github.com/danielzuegner/robust-gcn)
    
### Relevant Workshops


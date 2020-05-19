# 大规模GNN和异构图神经网络

### GCN

* [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/pdf/1609.02907.pdf)
* Tensorflow implementation: https://github.com/tkipf/gcn
* Pytorch implementation: https://github.com/tkipf/pygcn

| Dataset |      Task      | Heterogeneous |  Nodes |  Edges  |
|:-------:|:--------------:|:-------------:|:------:|:-------:|
|   NELL  | Classification |       No      | 65,755 | 266,144 |





### Cluster-GCN

* [Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks](https://arxiv.org/pdf/1905.07953.pdf)
* Tensorflow implement: https://github.com/google-research/google-research/tree/master/cluster_gcn
* Pytorch implement: https://github.com/benedekrozemberczki/ClusterGCN

|  Dataset |      Task      | Heterogeneous |    Nodes   |   Edges   |
|:--------:|:--------------:|:-------------:|:----------:|:---------:|
| Amazon2M | Classification |       No      | 61,859,140 | 2,449,029 |




### Graphsage

* [Inductive Representation Learning on Large Graphs](https://arxiv.org/pdf/1706.02216.pdf)
* Tensorflow implementation: https://github.com/williamleif/GraphSAGE
* Pytorch implementation: https://github.com/williamleif/graphsage-simple/

|  Dataset |      Task      | Heterogeneous |  Nodes  |   Edges   |
|:--------:|:--------------:|:-------------:|:-------:|:---------:|
| Citation | Classification |       No      | 302,424 | 1,383,590 |


### SGC

* [Simplifying Graph Convolutional Networks](https://arxiv.org/pdf/1902.07153.pdf)
* Tensorflow implementation https://github.com/zhouchunpong/Simplifying-Graph-Convolutional-Networks
* Pytorch implementation: https://github.com/Tiiiger/SGC

| Dataset |      Task      | Heterogeneous |  Nodes  |    Edges   |
|:-------:|:--------------:|:-------------:|:-------:|:----------:|
|  Reddit | Classification |       No      | 232,965 | 11,606,919|




### FastGCN

* [FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling](https://arxiv.org/pdf/1801.10247.pdf)
* Tensorflow implementation: https://github.com/matenure/FastGCN

| Dataset |      Task      | Heterogeneous |  Nodes  |    Edges   |
|:-------:|:--------------:|:-------------:|:-------:|:----------:|
|  Reddit | Classification |       No      | 232,965 | 11,606,919|


### VRGCN
* [Stochastic Training of Graph Convolutional Networks with Variance Reduction](https://arxiv.org/pdf/1710.10568.pdf)
* Tensorflow implementation: https://github.com/thu-ml/stochastic_gcn

| Dataset |      Task      | Heterogeneous |  Nodes  |    Edges   |
|:-------:|:--------------:|:-------------:|:-------:|:----------:|
|  Reddit | Classification |       No      | 232,965 | 23,446,803 |



### NGCF
* [Neural Graph Collaborative Filtering](https://arxiv.org/abs/1905.08108)
* Tensorflow implementation: https://github.com/xiangwang1223/neural_graph_collaborative_filtering

|   Dataset   |       Task      | Heterogeneous | Users  | Items  |  Nodes  |    Edges    |
|:-----------:|:---------------:|:-------------:|--------|--------|:-------:|:-----------:|
| Amazon-Book | Link-prediction |      Yes      | 52,643 | 91,599 | 144,242 | 2, 984, 108 |



### PinSage

* [Graph Convolutional Neural Networks for Web-Scale Recommender Systems](https://arxiv.org/pdf/1806.01973.pdf)

* Pytorch implementation: https://github.com/dmlc/dgl/blob/master/examples/pytorch/recommendation/rec/model/pinsage.py

这篇论文是一篇工业应用的论文，用的数据节点有上亿个



### GAS

* [Spam Review Detection with Graph Convolutional Networks](https://arxiv.org/pdf/1908.10679.pdf)

| Dataset |      Task      | Heterogeneous | Users     | Items      |  Comments  |
|:-------:|:--------------:|:-------------:|-----------|------------|:----------:|
|  Xianyu | Classification |      Yes      | 9,158,512 | 25,107,228 | 37,323,039 |


### L2-GCN

* [L2-GCN: Layer-Wise and Learned Efficient Training of Graph Convolutional Networks](https://arxiv.org/pdf/2003.13606.pdf)
* Pytorch implementation: https://github.com/TAMU-VITA/L2-GCN

|  Dataset |      Task      | Heterogeneous |    Nodes   |   Edges   |
|:--------:|:--------------:|:-------------:|:----------:|:---------:|
| Amazon3M | Classification |       No      | None | None |


### HAN 
* [Heterogeneous Graph Attention Network](https://arxiv.org/pdf/1903.07293.pdf)
* Tensorflow implementation: https://github.com/Jhy1993/HAN

| Dataset |      Task      | Heterogeneous | Movies    | Actors   |  Directors  |
|:-------:|:--------------:|:-------------:|-----------|------------|:----------:|
|  IMDB | Link Prediction |      Yes      | 4780 | 5841 | 2269 |



### HetGNN 

* [Heterogeneous Graph Neural Network](https://dl.acm.org/doi/pdf/10.1145/3292500.3330961)
* Pytorch implementation: https://github.com/chuxuzhang/KDD2019_HetGNN

| Dataset |      Task      | Heterogeneous |  Author     | Paper   | Venue  |
|:-------:|:--------------:|:-------------:|-----------|------------|:----------:|
|  Academic  | Classification/Link prediction |      Yes      | 160,713 |  111,409 |  150 |


### HGT

* [Heterogeneous Graph Transformer](https://arxiv.org/pdf/2003.01332.pdf)
* Pytorch implementation: https://github.com/acbull/pyHGT

| Dataset |      Task      | Heterogeneous | Nodes    | Egdes   |  
|:-------:|:--------------:|:-------------:|-----------|------------|
|  IMDB | Link Prediction |      Yes      | 178,663,927 | 2,236,196,802 | 


### GPNN

* [Graph Partition Neural Networks for Semi-Supervised Classification](https://arxiv.org/pdf/1803.06272.pdf)
* Tensorflow implementation https://github.com/Microsoft/graph-partition-neural-network-samples



| Dataset |      Task      | Heterogeneous | Nodes    | Egdes   |  
|:-------:|:--------------:|:-------------:|-----------|------------|
|  DIEL | Classification |     No      | 4,373,008 | 4,464,261 | 




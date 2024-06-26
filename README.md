

# FMRI Foundation Model

## Overview

This project focuses on pretraining foundation models that can easily adapt to downstream tasks for fMRI analysis.
In each directory, the `Pretrain_XXX.py` and `Finetune_XXX.py` scripts are the main functions for pretraining and fine-tuning a specific encoder, respectively.

## Pretrained Encoders

In this project, we pretrain several popular encoders on auxiliary fMRI scans. The pretrained encoders include:

1. Graph Convolutional Network (GCN)
2. Graph Attention Network (GAT)
3. Graph Isomorphism Network (GIN)
4. BrainGNN
5. BrainNetCNN
6. Spatio-Temporal Attention Graph Isomorphism Network (STAGIN)
7. Spatio-Temporal Graph Convolutional Network (STGCN)
8. GraphSAGE
9. Transformer
10. Modularity-constrained Graph Neural Network (MGNN)


## Usage
You can fine-tune pretrained encoders for various fMRI-based analysis.
Note that the `Finetune_XXX.py` script is just an example of how to finetune our pretrained encoders for classification tasks, and one can modify this code according to different downstream tasks.

Many thanks to the following public projects: 
[SimSiam](https://github.com/facebookresearch/simsiam),
[UCGL](https://github.com/mxliu/Unsupervised-Contrastive-Graph-Learning),
[GCN](https://github.com/tkipf/gcn)
[GAT](https://github.com/gordicaleksa/pytorch-GAT),
[Transformer](https://github.com/gordicaleksa/pytorch-original-transformer/tree/main),
[BrainGNN](https://github.com/xxlya/BrainGNN_Pytorch),
[BrainNetCNN](https://github.com/nicofarr/brainnetcnnVis_pytorch/tree/master),
[GraphSAGE](https://github.com/williamleif/graphsage-simple),
[STAGIN](https://github.com/egyptdj/stagin),
[STGCN](https://github.com/sgadgil6/cnslab_fmri).

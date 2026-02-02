# Less is More: Federated Graph Learning with Alleviating Topology Heterogeneity from A Causal Perspective

## Introduction

This repository contains the official implementation of the paper:

**_Less is More: Federated Graph Learning with Alleviating Topology Heterogeneity from A Causal Perspective_**

Federated Graph Learning (FGL) often suffers from **topology heterogeneity** across client-side subgraphs, which introduces redundant and spurious topological information and negatively affects the performance of federated models.

To address this issue, we propose **FedATH**, a novel federated graph learning framework from a **causal perspective**. FedATH aims to identify and extract **causal components** from client subgraphs, thereby reducing the impact of redundant topology information during federated training. By focusing on causally relevant structures, FedATH effectively improves robustness and generalization under heterogeneous graph distributions.

---

## Requirements

The required environment configuration is as follows:

- Python == 3.9.12  
- PyTorch == 2.0.1  
- NumPy == 1.24.4  
- scikit-learn == 1.6.1  

You can install the dependencies using:

```bash
pip install torch==2.0.1 numpy==1.24.4 scikit-learn==1.6.1
```
## Running
To run the FedATH, execute the following command:
```bash
python main_fedath.py
```

# VIP-DECT: Virtual-mask Informed Prior for Sparse-view Dual-Energy CT Reconstruction
[![arXiv](https://img.shields.io/badge/arXiv-2504.07753-b31b1b.svg)](https://arxiv.org/abs/2504.07753)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
This repository contains the PyTorch implementation of the paper **"Virtual-mask Informed Prior for Sparse-view Dual-Energy CT Reconstruction"**.
> **Code Availability:** The source code is available at [https://github.com/yqx7150/VIP-DECT](https://github.com/yqx7150/VIP-DECT).


## Abstract
Sparse-view sampling in dual-energy computed tomography (DECT) significantly reduces radiation dose and increases imaging speed, yet is highly prone to artifacts. Although diffusion models have demonstrated potential in effectively handling incomplete data, most existing methods in this field focus on the image do-main and lack global constraints, which consequently leads to insufficient reconstruction quality. In this study, we propose a dual-domain virtual-mask in-formed diffusion model for sparse-view reconstruction by leveraging the high inter-channel correlation in DECT. Specifically, the study designs a virtual mask and applies it to the high-energy and low-energy data to perform perturbation operations, thus constructing high-dimensional tensors that serve as the prior information of the diffusion model. In addition, a dual-domain collaboration strategy is adopted to integrate the information of the randomly selected high-frequency components in the wavelet domain with the information in the projection domain, for the purpose of optimizing the global structures and local details. Experimental results indicated that the present method exhibits excellent performance across multiple datasets.

Key words—Dual-energy CT, sparse-view reconstruction, virtual mask, dual-domain, collaborative strategy.

## Method Overview


## Acknowledgements
This work was supported by the National Natural Science Foundation of China 62122033 and the Key Research and Development Program of Jiangxi Province 20212BBE53001.


## Citation
```bibtex
If you find this work useful, please cite our paper:
@article{chen2025vipdect,
  title={Virtual-mask Informed Prior for Sparse-view Dual-Energy CT Reconstruction},
  author={Chen, Zini and Xiao, Yao and Zhang, Junyan and Wang, Shaoyu and Shi, Liu and Liu, Qiegen},
  journal={arXiv preprint arXiv:2504.07753},
  year={2025}
}

